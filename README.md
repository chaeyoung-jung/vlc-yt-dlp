# VLC youtubeDL (yt-dlp compatible)

A modified version of mjasny/vlc-youtubeDL.

This fork maintains the original VLC integration
while replacing youtube-dl with yt-dlp.

### Prerequisites
- A working `yt-dlp` installation (`yt-dlp` must be in `$PATH`)
-  Please update VLC to the latest version.

### Installation
Put yt-dlp.lua into:
- In Windows: `%APPDATA%\vlc\lua\playlist\`
- In Mac OS X: `/Users/%your_name%/Library/Application Support/org.videolan.vlc/lua/playlist/`
- In Linux: `~/.local/share/vlc/lua/playlist/`
    - Not tested on macOS or Linux.

### Usage
Simply open a YouTube link in VLC.

### Changes
- Replaced youtube-dl with yt-dlp (not delete youtube-dl option).
- Improved VLC playback compatibility by passing the original HTTP User-Agent.

### Credits
- Original project: [here](https://github.com/mjasny/vlc-youtubeDL)
- Original author: mjasny