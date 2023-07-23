---
permalink: /linkedit.html
layout: default
---

<h1 class="appName">LinkEdit</h1>
<p class="hero">Plain text haven.</p>

<img class="screenshot" alt="Two LinkEdit windows showing open text files" src="/images/linkedit-hero_2x.png" style="width: 1280px;"> 

<a href="https://apps.apple.com/app/id1597510262" style="display:inline-block;overflow:hidden;background:url(images/mac-app-store.svg) no-repeat;width:165px;height:40px;" class="badge" aria-label="Download on the App Store"></a>

Personal knowledge manager ([PKM][1]). Point to any folder on your Mac and manage your markdown notes. Create auto-updating links which can go in both directions. 

• Built-in file manager and plain text editor  
• Industry-leading privacy, zero tracking and third-party analytics  
• Optional sync with iCloud Drive, OneDrive or any other cloud service  
• Markdown preview  
• Quick Open with a search  
• Use the `linkedit://open` URL scheme to open individual notes from anywhere  
• Create Permanent Links between your notes [Pro]  
• Browse notes metadata, including backlinks with Links Inspector [Pro]  
• No subscriptions, 1 purchase to unlock LinkEdit [Pro]

## Native app

Features you can expect from any great Mac app.

• Three-column navigation  
• Multiple windows and tabs  
• Inline notes renaming  
• Drag and Drop  
• Find and Replace  
• macOS Spell Checking  
• Automatic theme switching  
• Low RAM usage  
• Small app size, less than 7 MB[^1]  
• Built with SwiftUI and AppKit

## Markdown
<img class="screenshot" alt="Editor window with preview on a right showing markdown features." src="/images/linkedit-markdown_2x.png" style="width: 912px;"> 

Basic [Markdown](https://daringfireball.net/projects/markdown/) preview.

## Permanent Links [Pro]
<img src="/images/linkedit-sidebar-badge-dark.png" alt="A sidebar with 2 notes which have badges, shutdown (4) and social (1)" style="width: 208px; height: 58px;">

Connect your notes using Permanent Links, and navigate back with backlinks. 

• LinkEdit will keep links working even after you rename or move linked notes  
• Navigate backlinks through the Links Inspector  
• Display the number of backlinks for every note right in the sidebar, it shows how important a note is  

### Auto-updating metadata

1. For linked notes with unique names, you can move them anytime from anywhere, including other apps and Finder
2. If one of the linked notes in your Default Folder has a repeating name, LinkEdit will use the full path to your note and will keep it up-to-date whenever possible. This means you can still move and rename your notes, however, this will only work when move or rename operations performed within the LinkEdit
4. Starting from version 1.2, links metadata is stored as JSON in every Default Folder, inside the `.linkedit` hidden directory. For example:

`~/Documents/Personal Notes/.linkedit/links.json</code>`

5. Deleting linked notes will remove the link from the metadata
6. You can only link to a note within the Default Folder

## Sandbox

• Full macOS Sandbox support  
• Choose a folder with plain text files as your default  
• Change Default Folder from the Settings `command + ,`  
• You can switch between your recently opened folders  
• You can have only one Default Folder  
• LinkEdit will persist access to the Default Folder

## Support

Drop us a line via [email,](https://www.cocoa.productions/support) and follow LinkEdit on <a rel="me" href="https://mastodonapp.uk/@linkedit">Mastodon</a>.

<h2 id="privacy">Privacy Policy</h2>

1. Your notes are fully private to you.  
2. Zero third-party tracking and analytics, we only use optional to you Apple tools and services for crash data collection and marketing analytics.  
3. Fully local client, we don't own any server components.

Last Updated: Jun 24, 2023
  
<br>
<br>
<br>

[^1]: Obsidian is almost 400 MB, and Apple TextEdit is less than 3 MB.

[1]: https://en.wikipedia.org/wiki/Personal_knowledge_management