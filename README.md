# asodo
asodo is an audio downloader that simplifies fetching and converting YouTube audio using `yt-dlp`.

## Why?
I wanted a quick way to download songs with `yt-dlp` using just a keybind. Now, I can simply copy the URL of the song I'm listening to, press a keybind, and the download starts automatically.

## How It Works
1. Copies the YouTube URL from your clipboard.  
2. Retrieves the video title using `yt-dlp`.  
3. Notifies you before and after downloading.  
4. Downloads and converts the audio to your specified format in the target directory.  

## Dependencies
Make sure you have the following installed:  
- `yt-dlp`  
- `pyperclip`  
- `notify-send` (for desktop notifications)  

## Usage
1. Set your desired download directory and audio format in the script.  
2. Copy a YouTube URL to your clipboard.  
3. Run the script:  
   ```bash
   python3 asodo.py
   ```
