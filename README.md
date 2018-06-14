# YOLOv3-SaveVideo-New

The original YOLOv3 version can be obtained from the website：https://pjreddie.com/darknet/yolo/, but it does not save the output video which is detected by default.

So, this project gives a complete project which can save you output video,include your local test video and your webcam's test video. Only two files have been changed,include (./darknet/src/demo.c) and (./darknet/src/image.c). So,you can only change them in your YOLOv3 project.

Attention: Beacause the （./darknet/yolov3.weights） takes up too much memory space,so this project doesn't include the model,you can download it in the website：https://pjreddie.com/darknet/yolo/.

The run command is: ./darknet detector demo cfg/coco.data cfg/yolov3.cfg yolov3.weights input.mp4 -i 0 -out_filename outputVideo.avi

Welcome to contact me, good luck. Email:894568618@qq.com
