# OpenCV_Python_RaspberryPi
Notes to setup python3 cv2. Then I don't have to google around dependencies every time I set it up.

# Anaconda vs Pip

Best to use pip3 in Raspberry pi.

Anaconda opencv is still at 3.3.

Pip3 uses 3.4.


2019/9/26

Latest version of opencv is 4.1 for amd64 or x86. Not available yet for armv7, v6.

# Requirements

pip3

or 

anaconda


# Prep

sudo apt -y install python3-pip


# Installation

--pip3--

pip3 install --user opencv-python

For GSOC use opencv-contrib-python

pip3 install --user imutils


For opencv-python install dependencies from dependencies.txt in this github repo. This saves ton of time.

--Anaconda--

conda install opencv=3.3

conda install gilbertfrancois imutils

