# Smart Surveillance AI System Using ComputerVision
The aim of this project is to pave the way to explore the application of artificial intelligence to the surveillance industry which provides effective but cheaper AI-based products so that everyone from the biggest banks to small business owners can rip the benefits of AI for security purposes

## General Project idea:

## Scenario 1: Clothing Shops or Supermarkets
Assume a group of members actively stooling a few products by hiding the items in the
supermarket inside their own clothes from the shop. They were all aware that CCTV is
watching but without fear they engage in this kind of theft. So this is the most common
form of thread from small business to large scale business owners. For that, consider
that the model made by my team is deployed on a central system which is capable of
object detection, classifying threats according to their customer behavior levels, assigning
this threat level to a different category which will be color coded for easy identification
of what kind of actions will be initiated by the system. If our AI agent system identifies
any thread it will automatically send a secret alert/warning message to trusted contacts
including the shopkeeper, business owners,security guard, etc.

## Scenario 2: Bank
As usual, there will be security guards and cameras everywhere. But do you think they
have been 100% successful in stopping the armed robbery, No right? For that, consider
that the model made by my team is deployed on a central system which is capable of
object detection, classifying threats according to their threat levels, assigning this threat
level to a different category which will be color coded for easy identification of what
kind of actions will be initiated by the system. In this example, an Armed robber has
entered the building, eliminating the guards and taking everyone hostage, standard movie
example where you see some employee trying to push an alarm switch which calls the
cops, but they are risking a great deal doing that. But this is a special moment for our
AI-based service, when those robbers eliminated the guards using force and blackmailing
by showing weapons, our early warning system sent a red alert to the police
automatically. This eliminates every possible life-threatening action that should be taken
by any employee to call the backup.

## Bird’s EyeView of Our Action Plan
Convolutional Neural Networks are best when it comes to computer vision tasks on
images but hardly any surveillance project is dependent solely on images. Most of the
time it is more dependent on the videos that are captured from CCTVs or Live feed of
the video and we are required to video analyze it. So How to work around this
requirement? And answer is gained by knowing what video is made of. Any video is just a
composite of many images with little changes over time to show it as if it is in
movement, these images are known as frames

There is one attribute of video known as fps which means Frames per second. Higher
the number of fps more realistic the video seems but it also means higher fps video will
require more space as it is made up of more images or frames in a given one second
window. We can salvage this attribute for our idea. If we want to use image analysis on
video we can just extract frames from the video and then we will be left with a long
series of images with which we can work using CNN on them.

We can comprehend this workflow with different Deep learning algorithms from below given flowcharts

# YOLOV5 MODEL TRAINING FLOWCHART

![YOLOV5-MODEL-TRAINING-FLOW](https://user-images.githubusercontent.com/99796805/199208124-e7d5dbf9-4d64-4705-9972-91b286650378.jpg)

# DETECTRON2 MODEL TRAINING FLOWCHART

![YOLOV5-MODEL-TRAINING-FLOW-Copy](https://user-images.githubusercontent.com/99796805/199208896-54150973-16c9-409f-bb69-14922e124557.jpg)
