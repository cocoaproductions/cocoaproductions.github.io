---
permalink: /linkedit.html
layout: default
title: LinkEdit - Cocoa Productions
---

<h1 class="appName">LinkEdit</h1>
<p class="hero">Plain text haven.</p>

<img class="screenshot" alt="Two LinkEdit windows showing open text files" src="/images/linkedit-hero_2x.png" style="width: 1280px;"> 

Personal knowledge manager ([PKM][1]). Point to any folder and manage your Markdown and plain text notes. Create auto-updating links which can go in both directions. 

<a href="https://apps.apple.com/us/app/linkedit/id1597510262?itscg=30200&itsct=apps_box_badge&mttnsubad=1597510262" style="display: block; margin: auto; width: 25%; padding: 2em;">
    <img src="https://toolbox.marketingtools.apple.com/api/v2/badges/download-on-the-app-store/black/en-us?releaseDate=1661817600" alt="Download on the App Store" style="width: 245px; height: 82px; vertical-align: middle; object-fit: contain;" />
</a>

### Free Features
- Built-in file manager and plain text editor
- Industry-leading privacy, zero tracking and third-party analytics
- Sync with iCloud Drive or any other storage provider
- Markdown preview  
- Use the linkedit://open URL scheme to open individual notes from anywhere  
- Browse notes metadata, including backlinks with Links Inspector

### LinkEdit Pro, ($14.99, one-time purchase)
- Unlimited Permanent Links
- Editor customisation

### Native app

Features you can expect from any great Mac app.

- Three-column navigation  
- Multiple windows and tabs  
- Inline notes renaming  
- Drag and Drop  
- Find and Replace  
- macOS Spell Checking  
- Automatic theme switching  
- Low RAM usage  
- Small app size, less than 7 MB[^1]  
- Built with SwiftUI and AppKit

### Markdown
<img class="screenshot" alt="Editor window with preview on a right showing Markdown features." src="/images/linkedit-markdown_2x.png" style="width: 912px;"> 

Basic [Markdown](https://daringfireball.net/projects/markdown/) preview.

### Permanent Links [Pro]
<img src="/images/linkedit-sidebar-badge-dark.png" alt="A sidebar with 2 notes which have badges, shutdown (4) and social (1)" style="width: 208px; height: 58px;">

Connect your notes using Permanent Links, and navigate back with backlinks. 

- LinkEdit will keep links working even after you rename or move linked notes  
- Navigate backlinks through the Links Inspector  
- Display the number of backlinks for every note right in the sidebar, it shows how important a note is  

#### Auto-updating metadata

1. For linked notes with unique names, you can move them anytime from anywhere, including other apps and Finder
2. If one of the linked notes in your Default Folder has a repeating name, LinkEdit will use the full path to your note and will keep it up-to-date whenever possible. This means you can still move and rename your notes, however, this will only work when move or rename operations are performed within the LinkEdit
4. Starting from version [1.2,](/blog/linkedit-1.2) links metadata is stored as JSON in every Default Folder, inside the `.linkedit` hidden directory. For example:

`~/Documents/Personal Notes/.linkedit/links.json`

5. Deleting linked notes will remove the link from the metadata
6. You can only link to a note within the Default Folder

### Sandbox

- Full macOS Sandbox support  
- Choose a folder with plain text files as your default  
- Change Default Folder from the Settings `command + ,`  
- You can switch between your recently opened folders  
- You can have only one Default Folder  
- LinkEdit will persist access to the Default Folder

## Support

Please visit the [feedback](/feedback) page.

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