This project aims to build a real-time emotion detection system using deep learning techniques, specifically Convolutional Neural Networks (CNNs), to recognize facial emotions from images. The system utilizes popular Python libraries, including matplotlib, numpy, pandas, and Keras, for data manipulation, visualization, and model creation.

![image](https://github.com/AryanPrakhar/EmoDec/assets/34882308/751a5e0f-3483-4b1b-bab5-38ed58064c6c)


The trained model is deployed to perform real-time emotion detection using the camera feed. The Haar Cascade classifier is used to detect faces in the video stream, and the emotion labels are displayed on the detected faces. The program runs in a loop until the user stops the execution.

How to run the program in your system
1.	To run the code in your system, download all the files.
2.	Open main.py in your IDE and change the file path string of ‘face_classifier’ variable and ‘classifier’ variable to the directories containing ‘haarcascade_frontalface_default.xml’ and ‘model.h5’ respectively.
3.	Now save the main.py and run the script.
4.	A window would open up showing your camera feed and labelling your emotions in real-time.
5.	To close the window, stop the execution of the script.


