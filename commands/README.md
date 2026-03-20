



## Download music youtube videos:
Requirements: `sudo dnf install yt-dlp`

`cd ~/Music/ ; yt-dlp -x --audio-format mp3 --trim-filenames 25 "YOUTUBE-URL"`

Note: Make sure you have permission to download content from YouTube

## Play them:
Requirements: `sudo dnf install mpv`

`mpv ~/Music/ > /dev/null 2>&1 & cava`
