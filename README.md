This code was written and tested in Python2.7 using OpenCV3.2.0 runnin on Ubuntu14.04

First be sure of have the necessary packages: Scipy and Imutils.
You can get them easy doing:
$ pip install scipy
$ pip install imutils

The program will use your webcam to scan objects and measure it width, but to do that you have to have a reference object with known width being the first object from left to right. And then other objects will be measured.

To run your program just do that:
python object_size.py --camera INDEX_OF_YOUR_WEBCAM --width KNOWN_WIDTH

Example:
python object_size.py --camera 0 --width 2.5

Have fun!
