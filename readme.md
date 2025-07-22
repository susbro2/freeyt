# freeyt

**freeyt** is a simple web application that allows users to download YouTube videos as audio or video files. It is built with Flask and uses [yt-dlp](https://github.com/yt-dlp/yt-dlp) for downloading and converting media.

## Features

- Download YouTube videos as audio (best quality)
- Download YouTube videos as video (best quality, MP4)
- Clean, modern Bootstrap interface
- Download link provided after processing

## Requirements

- Python 3.7+
- Flask
- yt-dlp

## Installation

1. **Clone or download this repository.**

2. **Install dependencies:**
   ```
   pip install flask yt-dlp
   ```

3. **(Optional) For production, also install:**
   ```
   pip install gunicorn
   ```

## Usage

1. **Run the app:**
   ```
   python app.py
   ```

2. **Open your browser and go to:**
   ```
   http://127.0.0.1:5000/
   ```

3. **Enter a YouTube video URL, select Audio or Video, and click Download.**

4. **After processing, a download link will appear. Click it to save the file to your device.**

## Deployment

You can deploy this app to platforms like PythonAnywhere, Render, or your own VPS.  
See the deployment instructions in the previous responses or your chosen platform's documentation.

## Notes

- Downloaded files are saved in the `downloads` folder.
- For public deployment, consider adding file cleanup and security measures.
- This app is for educational and personal use only. Respect YouTube's Terms of Service.

## License

MIT License

---

**Made with