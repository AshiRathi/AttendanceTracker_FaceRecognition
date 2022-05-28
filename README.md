# AttendanceTracker_FaceRecognition + CHATBOT
The proposed project is a smart method for managing attendance and record-keeping using face recognition.
<img width="443" alt="image" src="https://user-images.githubusercontent.com/91864520/170821871-276dd02b-e00a-49a7-a576-4afc215c3e6d.png">

# INTRODUCTION:
Mr. Pablo Picasso, epitome of art, once quoted, “Who sees the human face correctly: the photographer, the mirror, or the painter?” - 
I'll add to it, its indeed the code. 

# FACE RECOGNITION:
Face is the representation of one’s identity. Today, it is considered to be the most natural of all biometric measurements . And for a good reason, we recognize ourselves not by looking at our fingerprints or irises, for example, but by looking at our faces.  Of course, other signatures via the human body also exist, such as fingerprints, iris scans, voice recognition, digitization of veins in the palm, and behavioral measurements.
Why face recognition, then? 
Facial biometrics continues to be the preferred biometric benchmark. That is because it is easy to deploy and implement and there is no physical interaction with the end-user. Moreover, face detection and face match processes for verification/identification are speedy.
How does face recognition work? 
Facial technology systems can vary, but in general, they tend to include four operational steps:
Step 1: Face detection
Step 2: Face analysis
Step 3: Converting the image to data
Step 4: Finding a match from the existing database

# ATTENDANCE TRACKING:
Every organization requires a robust and stable system to record the attendance of their students. and every the organization have their method to do so, some are taking attendance manually with a sheet of paper and some have adopted biometrics systems such as fingerprints, RFID cardreader, Iris system to mark the attendance. In the RFID card system, each employee is assigned a card with their the corresponding identity but there is a chance of card loss or an unauthorized person may misuse the card for fake attendance. While in other biometrics such as fingerprint, iris or voice recognition, they all are not 100% accurate.

# METHODOLOGY:

<img width="443" alt="image" src="https://user-images.githubusercontent.com/91864520/170821947-fb4c7fa7-e85d-4d91-b1b6-2fc0436e9721.png">

<img width="443" alt="image" src="https://user-images.githubusercontent.com/91864520/170821959-d8a8494f-06e6-466a-a5cb-7f000575e0f2.png">

<img width="443" alt="image" src="https://user-images.githubusercontent.com/91864520/170821965-348720ca-181c-4eb3-8a38-c9272f10c2f7.png">

<img width="443" alt="image" src="https://user-images.githubusercontent.com/91864520/170821975-11afeb1d-3766-49e7-803f-a60dc7cb4fd3.png">

<img width="443" alt="image" src="https://user-images.githubusercontent.com/91864520/170822171-64727000-bd38-4d04-a0c6-7bd36f03770b.png">

<img width="444" alt="image" src="https://user-images.githubusercontent.com/91864520/170822008-78d81dab-197e-4701-a23e-3c95538b8a47.png">

# LIBRARIES:
○ Numpy - could be a library for Python, adding support for multi-dimensional arrays and matrices, in conjunction with an enormous assortment of high-level mathematical functions to operate on these arrays.○ Pandas - is a fast, powerful, flexible, and easy to use open-source data analysis and manipulation tool, built on top of the Python programming language.○ Haar Cascade - is a machine learning object detection algorithm used to identify objects in an image or video and based on the concept of features proposed by Paul Viola and Michael Jones in their paper "Rapid Object Detection using a Boosted Cascade of Simple Features" in 2001.○ Datetime - It’s a combination of date and time along with the attributes year, month, day, hour, minute, second, microsecond, and info.○ Face_Recognition - Recognize and manipulate faces from Python or the command line with the world’s simplest face recognition library.○ OpenCV - a library of programming functions primarily geared toward real-time computer vision.
pip install opencv-contrib-python
pip install numpy
pip install pandas
pip install Pillow

# INSTRUCTIONS TO RUN:
○ First download or clone the project
○ Import the project to your favourite IDE
○ Create a python enviroment
○ Install all the packages
○ Run the project using the command line or your IDE Run Button

#RESOURCES
The facial features are registered into the database folder by using the facial recognition xml file from the ‘OpenCV’ python library. Once the features are registered, the model is trained using the gathered features. The facial features are fetched from the database and the face of the student is recognized by comparing with existing values in the database. Facial Recognition is done using ‘OpenCV’ python library, particularly using ‘haarcascade’ code.

<img width="442" alt="image" src="https://user-images.githubusercontent.com/91864520/170822095-2601e69e-168b-470b-aed1-3b1c63458881.png">

<img width="443" alt="image" src="https://user-images.githubusercontent.com/91864520/170822112-54df500a-a10c-48d9-8c53-007f8755d97f.png">

<img width="443" alt="image" src="https://user-images.githubusercontent.com/91864520/170822126-4d9c0500-e6c7-443f-abf2-531ebda37998.png">

