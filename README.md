# Almost Dark Grey/Colorfull Proton
![Header](almostdarkColorfullprotonpreview.webp "Almost Dark Colorfull Proton for Firefox")
![](almostdarkGreyprotonpreview.webp "Almost Dark Grey Proton for Firefox")
This is a simple fork all credits to https://github.com/CristianDragos/FirefoxThemes and https://github.com/datguypiko/Firefox-Mod-Blur

# How to download and install
1. [Click here to download](https://github.com/Neikon/FirefoxThemes/archive/master.zip) or Click in the big green button called "Code" and click in "download zip".
2. Open a new tab in firefox and write in url bar `about:support` you should see a list with your firefox data, You only need **"Profile folder"** , you can now click in "Open folder" button o copy the address to your profile folder.
    the address should be similar to following example depend of your system:
    + Linux - `$HOME/.mozilla/firefox/XXXXXXX.default-XXXXXX/`
	+ Windows 10 - `C:\Users\<USERNAME>\AppData\Roaming\Mozilla\Firefox\Profiles\XXX.default-XXX`
	+ macOS - `Users/<USERNAME>/Library/Application Support/Firefox/Profiles/XXXXXXX.default-XXXXXXX`
3. Go to that folder.
4. if there is no folder called `chrome`. Create it.
5. Inside the zip file you downloaded in the first step there are a folder, open.Now you can see two faolders, each one corresponds to a theme. Choose one and extract its **content** into the `chrome` folder.
    + it should look something like this: 
    ```
    chrome/
          |- useschrome.css
          |- useContent.css
          |- image/
    ```
6. Now go to firefox open a new tab and write `about:config` in the url bar
7. A dialog will warn you, but ignore it, just do it press the `I accept the risk!` button.
8. Search this `toolkit.legacyUserProfileCustomizations.stylesheets` and set to **true**.
9. Restart Firefox
10. That's all, after restarting you should be seeing your new topic

**If you see any things in white maybe you need to activate dark colors in firefox**
 + Go to Firefox 3 lines menu -> Customize
 + At the bottom of the page there is a button called `themes` click it and set to `Dark`

# Newtab page 
1. enable this in `about:config` -> `browser.newtabpage.activity-stream.newNewtabExperience.enabled` to make newtab looks like preview picture.

# Other proton entries that maybe you like it (optionals)
1. `browser.proton.enabled`
2. `browser.proton.tabs.enabled`
3. `browser.proton.appmenu.enabled`



