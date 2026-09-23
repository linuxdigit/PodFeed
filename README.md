# PodFeed #

- setup on separate account so testing not part of AshLind
- Doc on the approach uploaded - based on conversation with Gemini
- probably feasible to use mp4 files, but take up more space

# MP4 to MP3 #
Method 3: Extract audio from video using ffmpeg command line tool
Almost anything can be done on the terminal and most of the time, it requires just one command. In this case, ffmpeg can be used, which is a command line tool which can extract audio fromo the desired video with just one command.

To install ffmpeg on Ubuntu and Debian based distributions, run:

sudo apt install ffmpeg
To extract audio from an input video file using ffmpeg, use:

##Convert##
ffmpeg -i input-video-file output-audio-file
Replace <input-video> and <output-audio> with the corresponding paths along with appropriate file extensions. 

##Upload MP# File ##
