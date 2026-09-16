# yt-dlp tool

## Installation
open cmd terminal and type
```bash
winget install yt-dlp --source winget
```

## Update 
```bash
yt-dlp -U
```

## Download Videoes
- Default (Highest available audio/video) quality
```bash 
yt-dlp "URL"
```

- Desired Quality Download
1. First check all available qualities.
```bash
yt-dlp -F "URL"
```
2. Now note the IDs of both (audio and video) and place them next to -f in following command.
```bash 
yt-dlp -f 123+456 "URL"
```