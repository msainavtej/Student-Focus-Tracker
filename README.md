Student Focus Tracker

This project is a real-time computer vision system that monitors user focus using a webcam. It was built during a 30-hour hackathon (Inspira by HackForge, IIT Hyderabad).

The system detects facial features and estimates whether the user is focused or distracted. It continuously analyzes behavior and reacts based on focus levels.

What it does:-
Captures live video using webcam
Detects face and facial landmarks using MediaPipe
Estimates focus using:
Eye openness
Head direction (looking left/right/center)
Calculates a real-time focus score
Tracks how long the user stays distracted
Triggers alerts when distraction continues for too long
Logs data for later analysis

How it works:-

The system runs in a continuous loop:

Observe → Reads webcam input
Analyze → Extracts facial features
Decide → Computes focus score
Act → Shows alerts when needed
Log → Stores data in a CSV file

Tech Stack:-
Python
OpenCV
MediaPipe
CSV logging


Output Features
Real-time focus score display
Reason for distraction (eyes closed / looking away)
Duration of distraction tracking
CSV file with timestamped logs


Purpose of the Project

This project explores how computer vision can be used to build systems that don’t just observe, but also react in real time based on human behavior.

It demonstrates a basic form of an autonomous decision-making loop using visual input.

Note:-

This is a prototype built for learning and hackathon purposes. It is not a production-ready system.
