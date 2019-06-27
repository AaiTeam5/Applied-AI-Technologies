# Applied-AI-Technologies

Repo for the lecture "Applied Artificial Intelligence" at the University of Applied Sciences Esslingen created by [Dionysios Satikidis](mailto:dionysios.satikidis@gmail.com) and [Jan Seyler](mailto:Jan.Seyler@gmail.com).

Check out the Applied-AI [Wiki](https://github.com/MrDio/Applied-AI-Technologies/wiki) for detailed Information. First start with the chapters and intro to NN and DL.

# Human-Detection-AAI
Human Detection für the Module AAI 

Needed Hardware
1. Raspberry 3 
2. PiCam 
3. Intel Compute Stick

Needed Packete 
Installing OpenVINO on the Raspberry Pi and performing object detection with the Movidius Neural Compute StickShell
$ sudo apt-get install build-essential cmake unzip pkg-config
 
Installing OpenVINO on the Raspberry Pi and performing object detection with the Movidius Neural Compute Stick
$ sudo apt-get install libjpeg-dev libpng-dev libtiff-dev
$ sudo apt-get install libavcodec-dev libavformat-dev libswscale-dev libv4l-dev
$ sudo apt-get install libxvidcore-dev libx264-dev

Installing OpenVINO on the Raspberry Pi and performing object detection with the Movidius Neural Compute StickShell
$ sudo apt-get install libgtk-3-dev

Installing OpenVINO on the Raspberry Pi and performing object detection with the Movidius Neural Compute StickShell
$ sudo apt-get install libcanberra-gtk*

Installing OpenVINO on the Raspberry Pi and performing object detection with the Movidius Neural Compute StickShell
$ sudo apt-get install libatlas-base-dev gfortran

Installing OpenVINO on the Raspberry Pi and performing object detection with the Movidius Neural Compute StickShell
$ sudo apt-get install python3-dev




Command to run the human detector
$ python3 openvino_real_time_object_detection.py --prototxt MobileNetSSD_deploy.prototxt \--model MobileNetSSD_deploy.caffemodel

Source: https://www.pyimagesearch.com/2019/04/08/openvino-opencv-and-movidius-ncs-on-the-raspberry-pi/
Hackster.io : https://www.hackster.io/hse-aai-2019-team5/human-detection-on-raspberrypi-c28d68

Thanks to our contributors:
</br>
[D. Lagamtzis](https://github.com/umadbro96)</br>
[Peltzfa](https://github.com/peltzefa/)
