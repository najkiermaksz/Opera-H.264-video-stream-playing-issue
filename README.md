# Opera-H.264-video-stream-playing-issue
How to get Opera Browser play videos

1. Get a working libffmpeg.so file matching your Chromium version from either https://github.com/iteufel/nwjs-ffmpeg-prebuilt or https://archlinux.org/packages/community/x86_64/vivaldi-ffmpeg-codecs/
2. $ sudo cp libffmpeg.so /usr/lib/chromium-browser
3. $ sudo cp libffmpeg.so /usr/lib/x86_64-linux-gnu/opera
4. Restart browser
