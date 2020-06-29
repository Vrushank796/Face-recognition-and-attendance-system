# faceRecognition

This repository contains code for facial recognition using openCV and python with a tkinter gui interface. If you want to test the code then run train.py file

Technology used :
-openCV (Opensource Computer Vision)
-Python
-tkinter GUI interface

Here I have worked  on Face recognition based Attendance Management System by using OpenCV(Python). One can mark thier attendance by simply facing in front of camera. 

How it works :

When we run train.py a window will open and it will ask to Enter Id and Enter Name. After entering  name and id ,you have to click on Take Images button. By clicking on Take Images ,seperate window will open to take images.This Id and Name will stored in the folder named StudentDetails and file name would be  StudentDetails.csv. It takes 60 images as sample and store them in the folder named TrainingImage.After completion it will notify that images are saved.
After taking image samples we have to click on Train Image button.Now,it will take few seconds to train machine for the images that are taken by clicking Take Image button and it  creates a Trainner.yml file and store in TrainingImageLabel folder.
Now,all initial setups are done. By clicking on Track Image button ,you can track images,and you would be take attendance. If face is recognised by system then Id and Name of person would be  shown on Image. Press Q(or q) to quit that window.After quitting  attendance of the  person would be stored in Attendance folder as csv file with name, id, date and time and it will be  also shown in tab at bottom.

Thanks.

