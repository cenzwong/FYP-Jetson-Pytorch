# Jetson-Nano-Log
## 08112019 Connecting with Camera again
With 5V/4A power source.
## 01112019 Connecting with the Camera
Navigate to the path
> nvdli-nano/hello_camera/csi_camera.ipynb
The Notebooks consist of
+ Markdown
+ Code
The Key board shortcut is 
+ Shift + Enter:  run the current cell, select below
+ Ctrl + Enter:  run selected cells
+ Alt + Enter:  run the current cell, insert below
+ Ctrl + S:  save and checkpoint

I am using the CSI camera, when I run the ipython notebook, the python will return busy. I suspend that the power problem, since I am using 5V/2A power source and the recommand power source is 5V/4A. Will go and buy a better source and USB camera for backup.

i use my USB camera and fail also

TODO buy official Power source and Logitech C270 Webcam

## 31102019 Configurating in headless mode
> Account:
> cenzth@gmail.com;
> This is my ac.

> Jetsonnano;
> 615*****

Headless mode, unsuccessful with opening the juptyer notebook on http://192.168.55.1:8888/. but able to access it though ssh(22),
Reflash the image again and skip the booting with monitor and directly using USB device mode.

The image inside the Deep Learning Course is different with the Jetson Nano Developer Kit SD Card Image. [NVIDIA DLI Jetson Nano SD Card Image](https://developer.download.nvidia.com/training/nano/dlinano_v1-0-0_image_20GB.zip) ==> dlinano_v1-0-0_image_20GB.zip

After flashing the new image onto Jetson Nano, open 192.168.55.1:8888, and password "dlinano". And successfully log in.

## 23102019 Flashing the Nano with the following image 
+ my [Jetson Nano Developer Kit SD Card Image](https://developer.nvidia.com/embedded/learn/get-started-jetson-nano-devkit#intro) ==> jetson-nano-sd-r32.2.1.zip

Program used to flash image: Etcher-Portable-1.4.6-x64.exe

I have boot it with monitor and USB and mouse, it can successfully boot up.

+++

Received Jetson Nano
