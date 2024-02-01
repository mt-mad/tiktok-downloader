# TikTok Video Downloader API

Welcome to the TikTok Video Downloader API! This API allows you to easily download TikTok videos without watermarks. It is built with Golang and designed to handle a large number of requests, capable of handling up to 1000 requests per second.

## Getting Started

### Starting the Server
To start the server, simply execute the provided file. There are no additional prerequisites needed.

```bash
./tiktok-video-downloader
```
## Making a Request
To download a TikTok video, send a POST request to the server with a JSON payload containing the TikTok video URL. The server will respond with the URL of the downloadable media or an error if any issues occur.

Example using cURL:
```bash
curl -X POST -H "Content-Type: application/json" -d '{"url":"https://www.tiktok.com/@filipovvprodd/video/7212634198098693382?q=gtr&t=1706791320828"}' 127.0.0.1:6969/download
```
## Response:

```bash
https://pride.nowmvideo.com/download/bLc-U-8L9hFwSfyLX04yjJOC8rYhLmXOvZDRzMxxdbqR-5FzzToM-VCg7F4vHSA0YAYHB0DEVsKqCUbs/7212634198098693382.mp4?hd=1
```

## Important Note
This repository does not contain the source code, and the API is not open source. The provided executable files can be directly executed to start the server. If you have any questions or concerns, please contact mt-mad.apis.

Happy downloading! 🎥🚀
