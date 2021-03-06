# MusicVideoPlayer
An IPA plugin for playing videos inside BeatSaber

# Usage

Select a song and difficulty and a Play icon will appear in the top right of the main screen. This takes you to the video detail view for the currently selected song. 

To begin adding a video, click search. A list of videos will appear, based on the chosen song's title and author. If these results aren't satisfactory use the refine button to type your own search terms. Select a video and press download. The video will be added to a queue and you can see the download progress in both the detail view and song list.

When the video has downloaded, the preview and offset buttons will allow you to fine tune the video offset to synchronise the beatmap audio to the downloaded video.

[Demo: Downloading a video](https://streamable.com/ayzjn)

In the settings menu you can enable automatic downloads, which will automatically download videos for new songs if the mapper specified a video. Download quality can be adjusted, but it is not recommended to go above Medium. You can also select a screen position from a set of presets.

While paused or in the menu, use your laser pointer and while holding the `grip` button to move the screen around. Your thumbstick or trackpad can be used to move the screen closer or further to you (Up/Down), or scale the screen (Left/Right)

[Demo: Moving the screen](https://streamable.com/dbtpn)


**Install Instructions:**
Extract the contents of the release zip to your Beat Saber Directory, merge folders as necessary.
Requires CustomUI, which can be obtained using the [ModSaber Installer](https://github.com/lolPants/modsaber-installer/releases)

# Features:
**Play Videos in Beat Saber**
* A custom json file `video.json` can be used in a song directory to detail a video
* These are automatically created for downloaded files
* Compatible with a wide range of video formats (check VideoPlayer Unity docs)
* Supports manual sync, looping, thumbnails and metadata

**Download Videos in game**
* Use the provided keyboard or the shortcut buttons to fill in your search query
* Adjustable video quality settings
* `video.json` can be shared and used to download the same video as another user (mappers can share `video.json` and players can automatically download the correct video and information)
* This plugin uses the application youtube-dl to do the heavy lifting, and will keep it up to date every launch

**Re-positionable screen**
* Preset positions are available in the settings menu
* Use the laser and `grip` button to re-position and rotate the screen to a custom position
* Use `Up` and `Down` on the track-pad or joystick to move the screen towards or away from you
* Use `Left` and `Right` to grow or shrink the screen
* Screen glows and affects the background, just like the existing lights
