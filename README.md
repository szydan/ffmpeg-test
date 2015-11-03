Why no sound in quicktime


ffmpeg -y -i video.mp4 -i audio.mp3  -c copy -map 0:0 -map 1:0 -shortest output.mp4

static ffmpeg build for osx downloaded from 
http://evermeet.cx/ffmpeg/ffmpeg-2.8.1.7z
