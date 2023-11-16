Object Detection Video
This is a project that uses OpenCV and YOLOv3 to detect objects in a video stream. It can detect 80 different classes of objects, such as person, car, dog, etc. The project also includes a GUI that allows the user to select the video source, adjust the confidence threshold, and view the results.

Requirements
To run this project, you need to have the following:

Python 3.6 or higher
OpenCV 4.5.3 or higher
Numpy 1.19.5 or higher
Tkinter 8.6 or higher
You also need to download the YOLOv3 weights file from [here] and place it in the same folder as the code.

Usage
To run the project, simply execute the following command:

Python
AI-generated code. Review and use carefully. More info on FAQ.

python object_detection_video.py
A GUI window will pop up, where you can select the video source from the following options:

Webcam: Use your webcam as the video source.
Video file: Select a video file from your computer.
IP camera: Enter the IP address of a camera that supports RTSP protocol.
After selecting the video source, you can adjust the confidence threshold using the slider. The confidence threshold is the minimum probability that an object is detected. The lower the threshold, the more objects will be detected, but also the more false positives will occur. The higher the threshold, the fewer objects will be detected, but also the more accurate they will be.

You can also pause and resume the video stream using the buttons below the slider.

The results will be displayed in a separate window, where you can see the video stream with bounding boxes and labels around the detected objects. You can also see the FPS (frames per second) and the number of detected objects on the top left corner of the window.

To exit the program, press the Q key on your keyboard or click the X button on the GUI window.
