# For segmenting videos into clips

ffmpeg -i <video_location>.mp4 -q:v 2 -start_number 0 %05d.jpg
