# Label-videos
modified code from Tensorflow label_image.py

put label_video and video_files the same folder as label_image and the image_file or you change the path accordingly,

> python tensorflow\examples\label_image\label_video.py --image <video_file_name>

line 133-139 is to select frames to be detected to decrease the delay time of the video as it takes my laptop around 1 second to finish the detection process, may delete or decrease the count number if your laptop is better than surface pro :)

