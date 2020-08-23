# Data perpartion:
Data perpartion is very important phase in any data science or machine learning project,if perpared data covers large scale of distrubution ,the application accuracy will be good .
 
Firstly we used data from internet that wasn't good enough ,so we created our custom data using scripts written in python.
 
### A) For shallow detector data we passed by two stages while creating data:
1-Egohands dataset:
it's dataset found online that contains labeled data for hands.

![] (images_used_in_readme\egohands.jpg)

Problem:The hand was detected in palm positions only ,so we need to find another solution

2-Creating our custom data:
 
-In this stage we have made script that opens the camera ,while running the script press n then give a folder name ,this name is used by script to create a folder and save images inside it,then press s to start taking images and saving them inside the folder.
 
-Then we took these images and start labeling it using  label_Img application by drawing a green box around the hand.
 
-we can make using that script more samples which leads to better accuracy
![Labeling images manually](images_used_in_readme\label_img)



###  B) For the deep classifier data:

1)In this stage we take dataset from internet:
Static Hand Posture Databases,Jochen Triesch Static Hand Posture Database.
-It was Low Quality Dataset which leads to bad accuracy.
![](images_used_in_readme\internetDeep)
