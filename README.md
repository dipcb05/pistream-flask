# pi-stream


This is a simple flask app to stream live a pi camera feed from Raspberry Pi. It can run in any PC also. The stream is based on opencv. 

Connect your pi to the power. Open terminal and run: 

```
http://0.0.0.0:5000 
```
The ip can be changed. Look on the main.py file. 

## Dependencies

* Raspberry Pi 4, 2GB is recommended for optimal performance. However you can use a Pi 3 or older, you may see a increase in latency.
* Raspberry Pi 4 Camera Module or Pi HQ Camera Module (Newer version)
* Python 3
* For run in PC, 4GB ram is recommended. If you have GPU, you can see good performance. 

## Library dependencies
Install the following dependencies to create camera stream.

```
sudo apt-get update 
sudo apt-get upgrade

sudo apt-get install libatlas-base-dev
sudo apt-get install libjasper-dev
sudo apt-get install libqtgui4 
sudo apt-get install libqt4-test
sudo apt-get install libhdf5-dev

sudo pip3 install flask
sudo pip3 install numpy
sudo pip3 install opencv-contrib-python
sudo pip3 install imutils
sudo pip3 install opencv-python


```

