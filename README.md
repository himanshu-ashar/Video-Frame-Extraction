# Video-Frame-Extraction
A python script which creates images of videos, at the rate of frame per second of the total duration of a video.

Requirements:
Numpy
OpenCV 4.3.0

To extract frames, change the source directory mentioned in the notebook, check the variable SOURCE_DIR.
The destination directory must also be specified in DEST_DIR.

To change the maximum acceptable video length, change the condition for total_seconds. Default has been set at 25 seconds.
To change the size of the image created, change the parameters in resize. Default has been set at 200x200.

All the above specifications have been clearly indicated in the code using comments.

The code extracts one frame per second of the video.
Within the destination directory, a folder is created for each video, within which a .jpg format of each image is created.
