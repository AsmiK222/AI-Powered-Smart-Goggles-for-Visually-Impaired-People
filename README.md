# AI-Powered-Smart-Goggles-for-Visually-Impaired-People
This project is to develop AI-powered smart goggles that assist visually impaired individuals in safe and independent navigation. The system integrates Robotics and Mathematical optimization to provide real-time guidance without internet dependency.
The project, "AI-Powered Smart Goggles for Visually Impaired People," aims to enhance the independence and safety of visually impaired individuals by enabling hands-free, real-time navigation without requiring internet access. Here's an overview:

Objective:
The smart goggles integrate AI, robotics, and mathematical optimization to provide:

Obstacle detection using YOLOv11 for object recognition and ultrasonic/infrared sensors for depth and low-light detection.
GPS-based navigation with the A* algorithm for optimal route calculation.
Voice command interface for destination input, making the system hands-free.
Real-time feedback via audio instructions and haptic feedback using vibration motors

Literature Review:
The project addresses limitations in existing solutions by:

Using YOLOv11 for accurate obstacle detection and depth awareness.
Integrating IR sensors for night-time usability.
Ensuring offline functionality for reliable use without internet dependency.
Employing Raspberry Pi 4 and Pi Camera for cost-effective implementation suitable for both indoor and outdoor navigation.

Research Gaps Addressed:
User-Specific Customization – Future work involves customizable alert settings.
Night-Time Performance – Plans to integrate thermal cameras for improved low-light detection.
Processing Efficiency – Considering hardware accelerators like Google Coral TPU.
Wearability – Improving battery placement for comfort.
Multilingual Support – Expanding voice recognition to multiple languages.

Methodology:
Object Detection:
Using YOLOv11 for real-time object recognition, enhanced by Singular Value Decomposition (SVD) for noise reduction and accuracy.
Navigation:
Neo-6M GPS module for real-time location tracking.
A algorithm* for dynamic pathfinding and obstacle avoidance.

Obstacle Detection:
Ultrasonic sensors for accurate distance measurement.
IR sensors for low-light obstacle detection.
Data fusion from both sensors for enhanced accuracy.

Feedback System:
Voice instructions using Text-to-Speech (TTS) for navigation.
Vibration motors for haptic alerts, with intensity varying by obstacle proximity.

Hardware Components:
Raspberry Pi 4 as the processing unit.
Raspberry Pi Camera for image capture.
Neo-6M GPS for navigation.
Ultrasonic and IR sensors for obstacle detection.
Vibration motors for haptic feedback.
Headphones and microphone for audio navigation and voice commands.
10,000mAh battery for portable power.

Software Stack:
Python for AI integration and sensor communication.
YOLOv11 model for object detection.
OpenCV for image processing.
PyTorch or TensorFlow for deep learning tasks.
A Algorithm* for navigation pathfinding.
pyttsx3 for Text-to-Speech.
