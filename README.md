# Real-time-Face-Recognition

This repository contains a real-time face recognition system implemented in Python, leveraging OpenCV and the face_recognition library. 

The project's primary goal is to accurately identify known individuals from a live webcam feed and to detect and manage unknown faces. Key features include: 

Real-time Face Detection and Recognition: Utilizes OpenCV for video capture and frame processing, combined with the face_recognition library for robust face detection and recognition based on facial embeddings. 
Known Face Identification: Compares detected faces against a pre-loaded database of encoded faces, identifying known individuals and displaying their names in real-time. 
Unknown Face Detection and Alerting: When an unfamiliar face is detected, the system triggers a visual alert on-screen and plays an audio alert (using winsound). 
Unknown Face Video Recording: Automatically records a short video clip when an unknown face is detected, providing visual evidence for review. 
Post-Processing of Unknown Faces: After the webcam feed is closed, the system displays captured images of unknown faces, prompting the user to identify them and potentially add them to the known faces database for future recognition. 
Efficient Real-time Processing: Designed for speed and efficiency to ensure smooth real-time performance.
