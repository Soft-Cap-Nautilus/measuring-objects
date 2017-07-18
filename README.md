This codes were written and tested in Python2.7 using OpenCV3.2.0 running on Ubuntu14.04


First be sure of have the necessary packages: Scipy and Imutils.


You can get them easy doing:

$ pip install scipy

$ pip install imutils


The program object_size.py will use your webcam to scan objects and measure it width, but to do that you have to have a reference object with known width being the first object from left to right. And then other objects will be measured.

To run this program just do that:

python object_size.py --camera INDEX_OF_YOUR_WEBCAM --width KNOWN_WIDTH


Example:

python object_size.py --camera 0 --width 2.5

The program distance_to_camera.py will use your webcam to scan an object and measure it distance to camera, but to do that you have to take a shot of the object pressing ESC in a known distance and have to know it width. And then just input the values on command line to see after that your camera scaning the object end measuring it distance to camera.

To run this program just do that:

python distance_to_camera.py

This project was based on:

http://www.pyimagesearch.com/2016/03/28/measuring-size-of-objects-in-an-image-with-opencv/
http://www.pyimagesearch.com/2015/01/19/find-distance-camera-objectmarker-using-python-opencv/

Have fun!
