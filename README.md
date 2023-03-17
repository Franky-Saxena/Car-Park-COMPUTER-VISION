# Car-Park-COMPUTER-VISION


Through this project we are trying to help the society as there is any free space for parking the car.

In this project we have created two files of python first is `parkingspacepicker.py` and `main.py`.

In the `parkingspacepicker.py` file we wrote a code to manually pick the parking spaces by just left click of the mouse and and remove the mark rectangle box through right click of the mouse.

So After dumping the locations of the car parking into the `CarParkPos` then we loaded that coordinates into the `main.py` and there are just counting the values of pixels into that rectangle boxes after converting the images into the low level.

So, according to counted pixel values we will predict the parking space is empty or not.

## Modules used:
* cv2(OpenCV)
* cvzone
* pickle
* numpy

## To watch the working of the carpark and free spaces
run a following command in command prompt
```
python main.py
```
## Deployment
```
1. First of all we will pick the parking spaces on the images of that we video manually.
2. we will load the coordinates into the main file
3. calculating the pixel values into rectangle boxes.
4. then we will predict the spaces are empty or not.
```


## Demo

![App Screenshot](https://raw.githubusercontent.com/Franky-Saxena/Car-Park-COMPUTER-VISION/main/Untitled1.png)
