To merge video.mp4 with audio.mp3 

static ffmpeg build for osx downloaded from     
http://evermeet.cx/ffmpeg/ffmpeg-2.8.1.7z

```
ffmpeg -y -i video.mp4 -i audio.mp3  \
-c:v copy -c:a aac -strict experimental \
-map 0:v:0 -map 1:a:0 output.mp4
```

