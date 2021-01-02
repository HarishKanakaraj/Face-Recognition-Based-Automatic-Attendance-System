# Face-Recognition-Based-Automatic-Attendance-System
This repository contains code for Facial Recognition using opencv and python with a tkinter GUI interface. If you want to test the code then run train.py file

Technology: -openCV (Computer Vision) -Python -tkinter GUI interface

I am working on Face recognition based Automatic Attendance System by using OpenCV(Python). One can mark attendance by simply facing the camera and automatically attendance is timestamped in excel sheet.

Working :

When we run train.py a window is opened and ask for Enter Id and Enter Name. After that we have to click Take Images button. By clicking Take Images camera of webcam is accessed and it start taking image samples of person.Id and Name is stored in folder StudentDetails in a comma separated format and  file name is StudentDetails.csv. It takes 60 images as sample and store them in folder TrainingImage.After completion it notify that images are saved. After taking image sample we have to click Train Image button.Now it take few seconds for training the images and creates a Trainner.yml file and store in TrainingImageLabel folder. Now all initial setups are done. By clicking Track Image button webcam of  machine is opened again. If face is recognised by system,then Id and Name of person is shown on Image. Press Q(or q) for quit this window.After quitting it attendance of person will be stored in Attendance folder as csv file with name, id, date and time and it is also available in window.
