# mdash

**mdash** is a lightweight Chrome extension which aims to replace the **New Tab** page with a light dashboard linked with your bookmarks.  

<img src="http://f.cl.ly/items/3H2K273T191W0D0N1v3M/dashboard-v0.2.png" alt="Dashboard" width="800" />

# Installation

## Latest 'stable' version (packed)

1. [Download the latest packed version of the extension](https://github.com/romac/mdash/downloads)  
2. Allow Chrome to download the .crx file by clicking **Continue** in the download bar.  
3. Install the extension by clicking **Install** in the pop-up window.

## Latest version (from source)

1. Clone the repository.  
   `$ git clone https://romac@github.com/romac/mdash.git`
2. Open Chrome and go to `chrome://extensions`  
3. Toggle the **Developer mode**.  
4. Click **Load unpacked extension...**  
5. Select the previously cloned repository.  

# Usage

## First time

Once the extension is installed, just open a new window to activate it.  
You'll now see an empty dashboard. This is needed in order to enable to extension to create a special folder named **[Dashboard]** in the **Other Bookmarks** folder.  

## Add a section

To add a section to the dashboard, open the **Bookmarks Manager** and browse to `/Other Bookmarks/[Dashboard]/`.

Each section is represented by a folder. As it is currently not possible to attach metadata to a folder, it's name will be used to determine in which columns the section should appear.  

Folders prefixed with the `+` character will be displayed on the left column, ones prefixed with a `-` will show on the right column.  

<img src="http://f.cl.ly/items/0y2g1e2v2p0Y150z0x1l/bookmarks.png" alt="Bookmarks Manager" width="600" />

## Add a bookmark

Browse any website you would like to add to the dashboard and click the star at the right of the address bar, then choose one of the previously created folders.  

<img src="http://f.cl.ly/items/3U2e2c0T421A2X1P1T43/star.png" alt="Add bookmark" />

# Planned features

- Drag bookmarks around to re-order them or put them in another section.
- Add a bookmark/section straight from the dashboard.
- Skins and maybe themes.

# Changelog

**Version 0.7.2** - UX improvements  
**Version 0.7.1** - Bugfix  
**Version 0.7.0** - Add/edit/remove bookmarks directly from the dashboard  
**Version 0.6.3** - Bugfix  
**Version 0.6.2** - Little UX improvements  
**Version 0.6.1** - Implement bookmarks edition  
**Version 0.5.4** - Cosmetic improvements  
**Version 0.5.3** - Bugfix  
**Version 0.5.2** - Icons  
**Version 0.5.0** - Rewritten from scratch  
**Version 0.1.0** - First public version  

# License

**mdash** is licensed under the [MIT license](http://www.opensource.org/licenses/mit-license.php).

# Credits

Brought to you with love by [@P45C4L](http://twitter.com/P45C4L) and [@_romac](http://twitter.com/_romac).  
Many thanks to [@ntzog](http://tzog.ch) for the icon ! It's beautiful, isn't it ?

mdash makes a great use of the awesome UI components from [UIKit](http://visionmedia.github.com/uikit/) by [@visionmedia](http://github.com/visionmedia).
