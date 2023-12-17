# Install_OpenCV_Python
Install Opencv Python on Raspberry Pi with Video Streaming Example
[![Video](https://img.youtube.com/vi/y80I7bL2M5E/maxresdefault.jpg)](https://www.youtube.com/watch?v=y80I7bL2M5E)
## Commands for installing OpenCV-Python :

### STEP 1 :   Check for Python 3 using terminal:

`python3 --version`


### STEP 2 :   Enter the command below into terminal:
``
sudo apt-get install build-essential cmake pkg-config libjpeg-dev libtiff5-dev libjasper-dev libpng-dev libavcodec-dev libavformat-dev libswscale-dev libv4l-dev libxvidcore-dev libx264-dev libfontconfig1-dev libcairo2-dev libgdk-pixbuf2.0-dev libpango1.0-dev libgtk2.0-dev libgtk-3-dev libatlas-base-dev gfortran libhdf5-dev libhdf5-serial-dev libhdf5-103 python3-pyqt5 python3-dev -y
``

### STEP 3 :   Enter the next command:

`pip3 install opencv-python`


### STEP 4 :   Open Python3  and check for cv2 in the Terminal ( (just type below commands and press enter in sequence ):
```
python3
import cv2
cv2.__version__
```
