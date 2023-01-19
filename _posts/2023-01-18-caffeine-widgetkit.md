---
layout: post
title: "Reengineering Caffeine++ Complications with WidgetKit"
date: 2023-01-18T17:0:8+0000
---

I've been [writing](https://www.cocoaswitch.com/2022/10/12/caffeine++-2.2/) about challenges I faced when trying to use `WidgetKit` for Apple Watch complications. With the upcoming update 2.5, we will finally ship watchOS 9 widgets inside Apple Watch app including the  rectangular family which was previously available only on iOS Lock Screen.

<img src="{{site.url}}/images/new-complications.png" width="100%" alt="New watch complication which shows number of drinks, mg, and last time updated">

After I implemented all the widgets families, all I needed to do is to add a new target and embed it inside Apple Watch app.

<img src="{{site.url}}/images/xcode-watch-target.png" width="100%" alt="Frameworks, Libraries, and Embedded Content including .appex extension">

This was an interesting journey that started with version 2.2. The first issue I had to overcome is automatic migration. This didn't work at all during my testing last year. I am not sure why it started working, it could be improved Xcode 14.2 or could be that I didn't had WidgetKit counterpart for every legacy complication. 

The next issue I had was related to performance, and I was able to resolve it by performing all heavy lifting in the app target and then saving the data model into a shared user defaults container, it's just an array with decodable objects. I am also able to calculate how the amount of caffeine will change over time which enabled me to generate a widget timeline. This is one of the features I am adding in the new version and having a single place to implement it is a relief. The advantage of `WidgetKit` is that I can share business logic between iOS widgets and watchOS complications.

Because `WidgetKit` is a new framework I found some limitations. I wasn't able to ship rounded complication because [there's no counterpart for `CLKComplicationTemplateGraphicCornerStackText`,](https://developers.apple.com/forums/thread/717599) and `.accessoryInline` widget family [uses only first `Text` node.](https://stackoverflow.com/q/73887649/1162044)

Now I achieved something which I am proud to ship, Caffeine++ 2.5 is currently in the App Store review.
