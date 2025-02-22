# Attendance-management-system-using-face-recognition-

-Built an AI-powered system for live attendance recording using OpenCV, exporting results to Excel Sheet.

-Libraries: Pandas, Haar Cascade, Face recognition, OpenCV.

--------------------------------------------------------------------------------------
----Overview of project-----

-After you run the project you have to register your face so that system can identify you, so click on register new student

-After you click a small window will pop up in that you have to enter you ID and name and then click on Take Image button

-After clicking Take Image button A camera window will pop up and it will detect your Face and take upto 50 Images(you can change the number of Image it can take) and stored in the folder named TrainingImage. more you give the image to system, the better it will perform while recognising the face.

-Then you have to click on Train Image button, It will train the model and convert all the Image into numeric format so that computer can understand. we are training the image so that next time when we will show the same face to the computer it will easily identify the face.

-It will take some time(depends on you system).

-After training model click on Automatic Attendance ,you have to enter the subject name and then it can fill attendace by your face using our trained model.

-It will create .csv file for every subject you enter and seperate every .csv file accoriding the subject

-You can view the attendance after clicking View Attendance button.

-It will show record in tabular format.

--------------------------------------------------------------------------------------
---Code Requirements---

Python 3.6+

Opencv(pip install opencv-python)

Tkinter(Available in python)

PIL (pip install Pillow)

Pandas(pip install pandas)

Numpy(pip install numpy)

Pillow (pip install Pillow)

--------------------------------------------------------------------------------------
haarcascade_frontalface_default.xml  ->>>> 

Where to Get It?
This file is included with OpenCV and is located in:
<opencv-installation-path>/data/haarcascades/
Or download it from OpenCV's GitHub:
🔗 https://github.com/opencv/opencv/tree/master/data/haarcascades
------------------------------------------------------------------------------------------

Editor - Visual studio code

--Notes--
*It will require high processing power
*Noisy image can reduce your accuracy so quality of images matter.
