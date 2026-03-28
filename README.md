# driver-drowsiness-detection

## Overview
This project presents a real-time driver drowsiness detection system developed using computer vision techniques. The system monitors facial features such as eye blinking and yawning to identify signs of fatigue and alert the driver to prevent potential accidents.

## Motivation
Driver drowsiness is a major cause of road accidents worldwide. This project aims to provide a simple, efficient, and real-time solution to detect fatigue and improve road safety using non-intrusive methods.

## Key Features
- Real-time face detection using webcam
- Eye blink detection using Eye Aspect Ratio (EAR)
- Yawning detection based on lip distance
- Audio alert system for driver notification
- Lightweight and efficient (no custom model training required)

## Technologies Used
- Python  
- OpenCV  
- Dlib  
- NumPy  
- Imutils  
- Pygame  

## Methodology
The system uses Dlib’s 68-point facial landmark detector to extract key facial features. Eye Aspect Ratio (EAR) is calculated to monitor blinking patterns, while the distance between upper and lower lips is used to detect yawning. If predefined thresholds are exceeded, the system classifies the driver as drowsy and triggers an alert.

## Project Workflow
1. Capture real-time video using webcam  
2. Detect face using Dlib  
3. Extract facial landmarks  
4. Compute Eye Aspect Ratio (EAR)  
5. Detect yawning using lip distance  
6. Classify driver state (Active / Drowsy / Sleeping)  
7. Trigger alert if necessary  

## Installation
1. Clone the repository:
git clone https://github.com/yourusername/driver-drowsiness-detection⁠�

2. Navigate to the project directory:
cd driver-drowsiness-detection

3. Install required libraries:
pip install -r requirements.txt

4. Download the pre-trained model:

https://drive.google.com/file/d/1YDd7OOlwxrgQGbE3murZ37J9qhDDMQYI/view?usp=drivesdk⁠

- Place it in the project directory

## Usage
Run the following command:
python Drowsiness_Detection_System.py

## Results
The system successfully detects drowsiness and yawning in real-time and alerts the driver through an audio signal. It performs reliably under normal lighting conditions.

## Limitations
- Performance may decrease in low-light environments  
- Fixed thresholds may vary between individuals  
- Requires proper camera positioning  

## Future Improvements
- Adaptive thresholding for personalized detection  
- Integration with deep learning models for improved accuracy  
- Mobile or embedded system deployment  

## Author
Ahsan Mehmood  
Bachelor of Science in Computer Science 
University of Agriculture Faisalabad (Sub-Campus Toba Tek Singh)
