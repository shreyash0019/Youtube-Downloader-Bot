# YouTube Downloader

This Python script allows you to download videos or audio from YouTube playlists. It uses the `pytube` library to download YouTube videos and the `moviepy` library to convert MP4 files to MP3.

## Requirements

- Python 3.x
- `pytube` library
- `moviepy` library

You can install the required libraries using the following commands:

```bash
pip install pytube
pip install moviepy
```

## Usage

1. Clone the repository:

```bash
git clone https://github.com/shreyash0019/Youtube-Downloader-Bot.git
cd Youtube-Downloader-Bot
```

2. Run the script:

```bash
python Youtube_Downloader-Bot.py
```

3. Follow the prompts to enter the YouTube playlist URL, the folder path where you want to save the videos, and the media type (audio or video). If you choose video, you will also need to specify the video quality (e.g., 720p, 1080p).

## Example

```bash
Enter the URL of the YouTube playlist: <playlist_url>
Enter the path of the folder where you want to save the videos: <folder_path>
Enter the media type (audio or video): video
Enter the quality of the video (e.g., 720p, 1080p): 720p
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details
