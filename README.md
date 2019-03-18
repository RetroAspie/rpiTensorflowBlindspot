# Raspberry Pi TensorFlow machine learning object detecting blind spot camera and warning system for vehicles
Made for the PA Pi Competition 2019

## The need and function of this project
![Cyclist](https://github.com/nuast/rpiTensorflowBlindspot/blob/master/documentation/pexels-photo-1458935.jpeg)
Cyclists and pedestrians are 15 times more likely than drivers to be killed on UK roads. In a society where we’re trying to desperately to promote environmentally friendly modes of transport, we’re instead unwillingly discouraging them with the safety risks. The cyclist safety movement usually focuses on the cyclist, wearing high-visibility clothing and covering bikes with flashing lights. However, these methods are only effective when seen. Many cyclists get seriously injured or even killed in blind spots, especially when the vehicles are turning, hence for the need of our project; an object detecting blind spot camera that warns both drivers and those at risk in the blind spot.

When a bike or pedestrian enters the blindspot (both identified in code as a “person”), the driver will be notified through an audible tone and text-to-speech message. The pedestrian or bike at risk will be warning through an 8x8 LED matrix hat attached to the Pi, placed in view of the vehicle’s blind spot that will flash a warning when detected, alerting the pedestrian or cyclist of the risk.

## Development Images
![Development](https://raw.githubusercontent.com/nuast/rpiTensorflowBlindspot/master/documentation/IMG_20190311_123431.jpg)
Editing the object detection code using nano.

## Installation guide:
### Easy method : flash image
Download the latest image off the releases page and flash it onto a SD card with atleast 32 GB. We'd reccomend using a class 3 SD card as they are faster but have less chance of being damaged.

### Hard method : building and installing
[Follow this tutorial](https://github.com/EdjeElectronics/TensorFlow-Object-Detection-on-the-Raspberry-Pi) to install tensorflow yourself, along with all other requirements. Then run `git clone https://github.com/nuast/rpiTensorflowBlindspot` to download the source files.

### Who made this and when:
Project start: Friday 1st March

Installation and building of Tensorflow and object models: Wednesday 6th March - Saturday 10th March

Programming: Monday March 11th - Monday March 18th

Deadline: Monday March 18th

This project was programmed, tested, documentated and completed in just over two weeks by [@ed6767](https://github.com/ed6767), [@retroaspie](https://github.com/retroaspie) and [@DRagaven](https://github.com/DRagaven)
