---
permalink: /linkedit.html
layout: default
---

<h2 class="appName">LinkEdit</h2>
<p class="hero">Say hello to your second brain.</p>

<a href="https://apps.apple.com/app/id1597510262" style="display:inline-block;overflow:hidden;background:url(images/mac-app-store.svg) no-repeat;width:165px;height:40px;" class="badge"></a>

<img src="/images/obsidius-promo.png" alt="Two LinkEdit windows showing open text files" style="width: 622px; height: 390px;">
<br>
LinkEdit is a minimalist personal knowledge manager (PKM). Point to any folder on your Mac and manage your markdown notes. Create auto-updating links between your files which can go in both directions. 

- Free app without subscription  
- One-time In-App Purchase to unlock unlimited backlinks
- No tracking or third-party analytics, your notes are fully private to you  
- Open file system storage   
- Compatible with iCloud Drive or Dropbox  
- Auto-updating backlinks  
- Basic Markdown preview  
- Open Quickly panel
- Customisable text editor  

<h3 id="privacy">Native App</h3>

Features you can expect from any great Mac app, thanks to SwiftUI and AppKit.

- Multiple windows and tabs
- Inline file renaming
- Drag and Drop
- Find and Replace
- System Spell Checking
- Automatic theme switching
- Low memory usage  

<h3 id="privacy">Markdown</h3>

LinkEdit Markdown parser uses SwiftUI.

<img src="/images/markdown.png" alt="Editor window with preview on a right showing markdown features" style="width: 535px; height: 386px;">

<h3>Backlinks</h3>

Build connections between your notes. 

- Links can be clicked when note is in a preview mode.
- Notes show amount of backlinks in a sidebar and total count of all links in bottom status bar
- List of backlinks is accessible in a separate "Inspector" window
- You can even rename your files and move them. Links will continue to work with  limitations described below.

1. Auto-updating links only can work when you rename your files within the LinkEdit.
2. You can move your files anytime as long as your file names are unique.
3. If your file name is not unique, LinkEdit will use full path to your note and will keep it up-to-date whenever possible. This means you can move the file and rename it, link path will update automatically. However you have to do it within LinkEdit.
4. Links and backlinks metadata stored as JSON files in the `meta` folder
```
/Users/username/Library/Containers/cocoa.productions.Obsidius
/Data/Documents/meta/
```
5. Deleting linked file will remove link from metadata
6. You can only link to a files within your root folder.

**At this moment LinkEdit backlinks requires your root folder to have a unique name.**
Navigate to the `meta` folder and delete a folder when necessary to prevent metadata mixing between 2 separate root folders AKA "vaults".

<h3>Sandbox</h3>

- LinkEdit supports Mac App Store sandbox, meaning it does not have access to your files unless you grant access in Finder
- LinkEdit remembers one folder as your default and retains access between app launches
- LinkEdit keeps a list of recently opened folders and you can work with them in multiple windows
- Access to non default folder is not saved after you quit LinkEdit, you will have to use the open dialog again
- You can change default folder in Obsidian preferences `Command + ,`.

<h3>Support</h3>

Drop me a line via [email,](https://www.cocoa.productions/support) and follow LinkEdit on [Twitter.](https://twitter.com/LinkEditApp)

<h3 id="privacy">Privacy Policy</h3>

- LinkEdit has no tracking or third-party analytics, your notes are fully private to you. 
- LinkEdit does not upload your notes anywhere. 
- You are welcome to sync the files you own with any tools available such as iCloud Drive.

Last Updated: August 20, 2022
