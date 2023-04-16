Drowsiness Detection System

Drowsy driving is a major cause of road accidents, especially for long-distance drivers. To address this issue, 
we have developed a device that can detect a driver's sleepy eyes and send an alert to the driver while also slowing down the vehicle. 
The device is a combination of hardware and software components, which work together to detect the driver's drowsiness and take appropriate actions to prevent accidents.

Software Components: 

The device consists of the following software components:

1.	Image Processing Algorithm: An image processing algorithm is used to analyze the images captured by the camera and detect the driver's drowsiness. 
The algorithm is designed to detect the following signs of drowsiness:

•	Slow eye blinking
•	Eye closure duration

2.	Various libraries are being used here such as:
•	Tensorflow
•	Keras
•	OpenCV
•	NumPy
•	Random
•	OS
•	PyGame

3.	Machine Learning Algorithm: A supervised machine learning algorithm is used to classify the level of drowsiness based on the features extracted from the image 
processing algorithm.

4.	Alert System: An alert system is used to notify the driver when he/she is drowsy.

5.	Sending alert to selected contacts for emergency cases.


Working Principle: 

The device works as follows:

1.	Initially, face is detected on the driver’s seat.
2.	Detection of eyes are done in the second step.
3.	Then, it tracks the movement of eyes.
4.	The images are captured by the camera and detects the driver's drowsiness using the image processing algorithm.
5.	The machine learning algorithm classifies the level of drowsiness based on the features extracted from the image processing algorithm.
6.	If the driver is drowsy, the alert system notifies the driver through text messages, buzzer system which can be easily installed on any wristbands or neckbands.
7.	Real-time processing
8.	Testing and Evaluation
9.	It sends the location of the driver to the selected contacts for emergency cases.


Conclusion: 
The device we have developed is a promising solution to the problem of drowsy driving. It can help prevent accidents caused due to drowsiness and improve the safety 
of drivers as well as passengers. 
