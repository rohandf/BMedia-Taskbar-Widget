# BMedia Taskbar Widget
This is a Rainmeter skin that lets you see what's playing, its progress, and album art/thumbnail.  
It also lets you seek to a point, control volume (New!) and pause, play, rewind and forward.

## Installation
1. First, make sure you have [Rainmeter installed](https://www.rainmeter.net/) and are familiar with its basic usage.
2. To install the skin, download the [latest release](https://github.com/rohandf/BMedia-Taskbar-Widget/releases/tag/rmskin) and install it (Having Rainmeter installed should let you simply open the file to start installation).  
3. If you want web browser compatibility, installing the WebNowPlaying browser extension is recommended. If this isn't installed, it won't detect browser players like the YouTube website or SoundCloud website.

      [Chrome Extension](https://chromewebstore.google.com/detail/webnowplaying/jfakgfcdgpghbbefmdfjkbdlibjgnbli)  (Should work with most chromium based browsers)

      [Firefox Extension](https://addons.mozilla.org/en-US/firefox/addon/webnowplaying/)

4. **THE SKIN WILL (probably, usually) NOT BE VISIBLE AFTER INSTALL. THIS IS INTENTIONAL BEHAVIOUR.**  
**To fix this problem, simply open a media player (Spotify, Youtube, etc) and play anything to make the skin show the details.**  
5. In the Rainmeter skin manager, change the `Position` to `Stay Topmost`. This allows the skin to be in front of the taskbar.  
6. If the `Draggable` option is on, you can click and drag the skin to wherever you like it.  
It's intended to be in the bottom left corner, taking up the empty space of a centered Windows 11 taskbar, but you can place it anywhere.

## Usage
- The skin hides itself when nothing is playing. It shows up whenever it detects one of [its supported players](https://wnp.keifufu.dev/supported-sites)  
- Hovering over the title will show the volume control. Clicking at its left edge sets the volume to 0, right edge sets volume to 100. Click anywhere between the volume control to set the volume to a specific percentage.
- Click anywhere in the progress bar to seek the media to that position.
- Rewind, Pause, and Forward buttons work as in any player.
- Middle Click (scroll wheel push down) on the skin to refresh it if it is not behaving correctly.

### Known Issues
- When the taskbar takes focus, the skin will not be visible, even for a little time after it loses focus. AFAIK there is no way to prevent this, as the taskbar's purpose when used is to always be visible over everything.
- Volume control does not work with Spotify.
