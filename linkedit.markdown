---
permalink: /linkedit.html
layout: default
---

<h2 class="appName">LinkEdit</h2>
<p class="hero">Plain text haven.</p>

<a href="https://apps.apple.com/app/id1597510262" style="display:inline-block;overflow:hidden;background:url(images/mac-app-store.svg) no-repeat;width:165px;height:40px;" class="badge"></a>

<img src="/images/obsidius-promo.png" alt="Two LinkEdit windows showing open text files" style="width: 622px; height: 390px;">
<br>

Personal knowledge manager ([PKM][1]). Point to any folder on your Mac and manage your markdown notes. Create auto-updating links which can go in both directions. 

• Built-in file manager and plain text editor  
• Industry-leading privacy, zero tracking and third-party analytics  
• Optional sync with iCloud Drive, OneDrive or any other cloud service  
• Markdown preview  
• Quick Open with a search  
• Use the `linkedit://open` URL scheme to open individual notes from anywhere  
• Create permanent links between your notes [Pro]  
• Browse notes metadata, including backlinks with Links Inspector [Pro]  
• No subscriptions, 1 purchase to unlock LinkEdit [Pro]

<h3 id="privacy">Native App</h3>

Features you can expect from any good Mac app

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

<h3 id="privacy">Markdown</h3>

Basic [Markdown](https://daringfireball.net/projects/markdown/) preview.

<img src="/images/markdown.png" alt="Editor window with preview on a right showing markdown features" style="width: 535px; height: 386px;">

<h3>Backlinks</h3>

Make connections between your notes. 

- Each note shows backlinks counter
- List of backlinks is accessible in the Links Inspector window
- Rename your notes and move them. LinkEdit will do its best to auto-update your links, but it's not possible in all scenarios

<h4>Auto-updating Metadata</h4>

1. Auto-updating links only can work when you rename your notes with LinkEdit
2. You can move your notes anytime as long as the names are unique
3. If your note name is not unique, LinkEdit will use the full path to your note and will keep it up-to-date whenever possible. This means you can move a note and rename it without breaking a link
4. Starting from version 1.2, links metadata is stored as JSON in every Default Folder, inside the `.linkedit` hidden directory. For example:
```
~/Documents/Personal Notes/.linkedit/links.json
```
5. Deleting linked notes will remove the link from the metadata
6. You can only link to a note within your root folder

**At this moment LinkEdit backlinks require your root folder to have a unique name.**
Navigate to the `meta` folder and delete a folder when necessary to prevent metadata mixing between 2 separate root folders AKA "vaults".

<h3>Sandbox</h3>

• Full macOS Sandbox support  
• Choose a folder with plain text files as your default  
• Change Default Folder from the Settings `command + ,`  
• You can switch between your recently opened folders  
• You can have only one Default Folder  
• LinkEdit will persist access to the Default Folder

<h3>Support</h3>

Drop us a line via [email,](https://www.cocoa.productions/support) and follow LinkEdit on <a rel="me" href="https://mastodonapp.uk/@linkedit">Mastodon</a>.

<h3 id="privacy">Privacy Policy</h3>

- Your notes are fully private to you.
- Zero third-party tracking and analytics, we only use optional to you Apple tools and services for crash data collection and marketing analytics.
- Fully local client, we don't own any server components.

Last Updated: Jun 24, 2023
  
<br />
<br />
<br />

[^1]: Obsidian is almost 400 MB, and Apple TextEdit is less than 3 MB.

[1]: https://en.wikipedia.org/wiki/Personal_knowledge_management