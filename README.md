# iot-watson-swift
If you like this project - give it a star!

This project covers Watson services (Visual Recognition, Speech to Text, Text to Speech),  Swift for iOS, Node.Red on Raspberry Pi, and on Bluemix, Cloudant NoSQL DB, MQTT protocol over Watson IoT Platform. It is good for beginners - I will show how to build everything from scratch. And if I use tools, I will explain why I need a hammer to nail the boards :-)

Shall you want to get your home robot (or simply Raspberry Pi - **called RPi** ) connected and augmented with Watson services, and controlled by a mobile app written in modern Swift language to manage your device and answer questions on the weather and golf? If the answer is yes - this is this project is for you.

## STEP 1. 
In this project first you need to connect RPi to Bluemix (over internet). Bluemix is the IBM Cloud - there are essential Watson and *common* services that we are going to leverage in our project. Add Twitter node for Social Network communications. Then you need to publish some data to Cloudant NoSQL DB.

[check the solution video for this step](https://youtu.be/qYP165NUaAs)

## STEP 2. 
Read the data from an iOS device in a Swift App.
[check the solution video for this step](https://youtu.be/dsNXsHrW5TA)

## STEP 3.
Furthermore you can add 2-way communications from Bluemix to RPi - to invoke picture grabbing (and if you happan to have the Raspcam - a RPi camera - we will use it to take a picture), and then I will send the picture from RPi to Bluemix (I will store the image in the DB). I will add the first Watson Service - the Visual Recognition - to our service to analyze picture.
[check the solution video for this step - part 1](https://youtu.be/me3LPnEuGEU)
[check the solution video for this step - part 2](https://youtu.be/XWjQH3dA8wI)

## STEP 4.
I will add a button and function to the iOS app to show the picture from the step 3 when the button "show the picture" is pressed.
[check the solution video for this step](https://youtu.be/7DvOP6iQPAg)

## STEP 5.
Finally I will connect the iRobot Create2 robot (based on iRobot Roomba 600 series) over the Serial-USB cable to RPi.
[check the solution video for this step](https://youtu.be/3oKUa3h4bAA)
## STEP 6.
I will invoke some commands from the iOS Swift app over MQTT.
check the solution video for this step in the video above.
## STEP 7.
Just to make things cooler - the Voice UI - I will ask our system about the weather forecasts - if it is nice - I will get the information on playing the golf conditions.
[check the solution video for this step](https://youtu.be/4t50vEexQeo)

So this simple 7 steps would allow us to augment a home appliance with Watson, and obtain a new Voice UI to create great User Experience (called as UX by many).
