# DragoonFox

A Firefox-CSS theme designed to replicate explorer tabs shown in the poplar Dragoon UI by KaLam1ty-AC, and made in the renowned DragoonX theme by niivu. A big thank you to MrOtherGuy for his helpful CSS snippets website.

## Setup

### Firefox css

1. In the searchbar type `about:config`. A dialog will be shown to you. Press the **I accept the risk** button.
2. Search for **`toolkit.legacyUserProfileCustomizations.stylesheets`**, **`layers.acceleration.force-enabled`**, **`gfx.webrender.all`**, and **`svg.context-properties.content.enabled`**. Change them to **True**
3. Go to your Firefox profile:
    - If you're on Linux: `$HOME/.mozilla/firefox/XXXXXXX.default-release/`
    - If you're on Windows: `C:\Users\<USERNAME>\AppData\Roaming\Mozilla\Firefox\Profiles\XXXXXXX.default-XXXXXX`
    - If you're on MacOS: `Users/<USERNAME>/Library/Application Support/Firefox/Profiles/XXXXXXX.default-XXXXXXX` 
4. Create a folder and name it **`chrome`** (with lowercase).
5. Then paste the `userChrome.css` and the `userContent.css` files into the folder.
6. You'll need to enable Title Bar in "Customize Toolbar" (found by right clicking tab bar)
7. Enjoy!

You should also set Firefox to "compact" and "dark mode". Those two options are available under menu > customize.

## Screenshots

### Browser

![oof](https://github.com/Blu3Jive001/DragoonFox/blob/master/Images/Firefox.png)

### Windows Explorer

![oof1](https://github.com/Blu3Jive001/DragoonFox/blob/master/Images/File_Explorer.png)
