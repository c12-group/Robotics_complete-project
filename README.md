# Robotics_complete-project
This folder includes robotics notes and presentations, Python scripts for tracking using HSV, Kalman Filter, Mediapipe, and YOLO methods, along with a complete smart-follow bot project (smart-follow-bot-main.zip) featuring backend logic and a React UI


This project is concerned with the creation of a real-time human-following robot that uses computer vision for intelligent behavior and interaction. Multiple perception techniques are integrated into the system, such as HSV-based color tracking, hand gesture recognition, and lightweight human pose estimation, for robust tracking and control. Gesture commands such as start, stop, and resume are realized using MediaPipe's hand module, while pose estimation provides better awareness of the robot's orientation and enhances interaction accuracy.   

While a hybrid tracking mechanism provides constant and smooth movement, fallback behaviors such as circular search may be triggered on losing the target. The optimization ensures that any added latency and computational load are minimized so that this scheme can work even on low-powered devices such as the Raspberry Pi. These robots are guided using visual feedback, which allows them to adapt to environmental changes and constantly and interactively respond.   

This work shows the effectiveness of combining simple vision-based techniques with advanced but computationally efficient pose recognition models to build a low-cost smart and interactive robotic assistant suitable for personal or educational purposes.
