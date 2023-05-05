# Sign-Language-Detection-System
A real time Sign Language detection system , for the cause of helping deaf and dumb people communicate with normal people and each other in a comfortable and easy manner in their day to day life.


Introduction
This project is a Real Time Sign Language Detection System made primarily for the Dumb and Deaf People. It is designed to recognize signs and gestures using a computer vision algorithm that analyzes live video feeds from a camera.


Technology

The project is built using the following technologies stack:
Python
OpenCV
Tensorflow
Convolutional Neural Networks (CNN)
Mediapipe Holistic Pointer-based Mapping
How it Works
The sign language detection system uses mediapipe mapping to predict the correct meaning of a provided sign under different circumstances. Unlike other techniques such as edge detection, the mediapipe pointer map system maps the distance between the pointers of the face, hands, and eyes to determine the correct interpretation of the sign. The system is designed to take into account the ambiguous nature of sign language, which can be subject to variations in interpretation.


Installation
To install the system, follow these steps:

Clone the repository to your local machine
Install the required packages and libraries mentioned in the main code file
Run the system
Usage
To use the system, follow these steps:


Run the system :-
Position yourself in front of the camera
Start signing with your hands
The system will detect and interpret your signs in real time


Future Work :-
This project is a work in progress, and there are several improvements that could be made in the future. Some areas for improvement include:

Currently the system is able to recognise very fewer signs , it requires more computational power in order to be trained for further signs.
Improving the accuracy of the sign detection algorithm
Expanding the system to support additional sign languages
Integrating the system with other assistive technologies


Additional features:-

Sentence Creator
In addition to recognizing individual signs and gestures, the system also includes a sentence creator feature. This feature is designed to generate complete sentences using the signs detected by the system. The sentence creator takes into account the grammatical structure of sign language and uses natural language processing techniques to generate meaningful sentences.
To use the sentence creator feature, simply sign a series of words or phrases in the desired order. The system will detect each sign and use them to construct a grammatically correct sentence. The resulting sentence will be displayed on the screen or read aloud using a text-to-speech engine, depending on your configuration.
The sentence creator feature is still a work in progress, and I am constantly working to improve its accuracy and performance. If you encounter any issues or have any suggestions for improvement, please feel free to contact.
