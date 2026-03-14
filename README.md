# GESTURE-TALK-PROJECT
# GESTURE TALK : ISL TO SPEECH IN REAL TIME
Indian Sign Language Recognition System using AI
Gesture Talk is an AI-powered sign language recognition system that detects Indian Sign Language (ISL) gestures in real time and converts them into readable text. The project uses computer vision and machine learning to bridge the communication gap between deaf/mute individuals and the general public.

# Problem:
Millions of people rely on sign language for communication, but most people do not understand it. This creates a communication barrier in everyday situations such as education, healthcare, workplaces, and public services. 

# Existing solutions often:
Require sensor gloves or special hardware
Support only American Sign Language (ASL)
Do not work efficiently in real-time environments
Gesture Talk aims to provide an affordable and accessible AI solution for recognizing Indian Sign Language gestures.
Solution:
Gesture Talk uses computer vision and machine learning to detect hand gestures from a webcam and translate them into text.

# The system:
Captures video from the webcam
Detects hands using MediaPipe
Extracts 21 hand landmarks
Uses a machine learning model to classify gestures
Displays the predicted gesture as text
This enables real-time sign language translation.

# Features:
Real-time gesture detection
AI-powered sign language recognition
MediaPipe hand landmark tracking
Machine learning gesture classification
Works with a normal webcam
Lightweight and fast system

# Expandable gesture dataset:
Technology Stack
Programming Language
Python
Libraries
OpenCV
MediaPipe
NumPy
Scikit-learn
TensorFlow / Keras (optional)
Tools
VS Code
Jupyter Notebook
Git & GitHub

# System Architecture
Webcam Input
     ↓
Frame Processing (OpenCV)
     ↓
Hand Detection (MediaPipe)
     ↓
Landmark Extraction
     ↓
Machine Learning Model
     ↓
Gesture Prediction
     ↓
Text Output


# Installation
1 Clone the Repository
git clone 
https://github.com/yourusername/gesture-talk.git
cd gesture-talk
2 Install Dependencies
pip install -r requirements.txt
3 Run the Program
python main.py
# Dataset:
The dataset consists of gesture samples representing Indian Sign Language signs. Hand landmark coordinates extracted from gestures are used to train the machine learning model.

# Applications
Communication for deaf and mute individuals
Sign language learning tools
Assistive technology systems
Human-computer interaction
Accessibility solutions
Future Improvement
Speech output from gestures
Sentence-level sign language recognition
Mobile application development
Deep learning based gesture models
Cloud deployment
SDG Impact
This project supports:
SDG 4 – Quality Education
SDG 10 – Reduced Inequalities
SDG 9 – Industry Innovation

# Author
Rohith Yadav G
AIML Specialization

License:This project is licensed under the MIT License.
