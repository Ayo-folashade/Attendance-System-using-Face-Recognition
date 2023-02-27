# Attendance System using Face Recognition

This is a Python script that uses face recognition to detect faces in real-time using a webcam and mark attendance for recognized faces. The script uses the face_recognition library to recognize faces and OpenCV to capture video frames from a webcam.

The program reads a directory of images containing the faces of the people you want to mark attendance for, and encodes each face. When a new face is detected in a webcam frame, the program compares it against the encoded faces and, if there's a match, records the attendance time in a CSV file.

The program uses text-to-speech to welcome recognized faces, and draws a green rectangle around their face in the video feed with their name and attendance status displayed.

This code can be a starting point for a variety of attendance systems, including those in schools, companies, and events.

Dependencies:

Python 3.6 or higher
OpenCV
face_recognition
numpy
pyttsx3
