# Attendance-OpenCV
This project automates the process of taking attendance in colleges using OpenCV for facial recognition and Tkinter for the GUI.


## Overview
The Attendance-OpenCV project is designed to simplify and automate the attendance-taking process in educational institutions. By leveraging facial recognition technology, haar cascade classifier and a user-friendly graphical interface, this tool ensures accurate and efficient attendance tracking.
## Features
- **Facial Recognition:** Utilizes OpenCV for detecting and recognizing faces.
- **User Interface:** Built with Tkinter for easy interaction.
- **Automated Attendance:** Automatically marks attendance based on recognized faces.
- **Data Management:** Stores student details and attendance records.

## Usage
1. Run the main application:
   ```sh
   python main.py
2. GUI Operations:
- **Register Student:** Add a new student's details and capture their face data. 
- **Take Attendance:** Start the camera and mark attendance for recognized students.

## Project Structure
- **Attendance/:** Stores attendance records.
- **StudentDetails/:** Contains details of registered students.
- **TrainingImage/:** Directory for storing captured images for training.
- **TrainingImageLabel/:** Stores labels for training images.
- **main.py:** The main script to run the application.
- **haarcascade_frontalface_default.xml:** Haarcascade file for face detection.
- **psd.txt:** stores credentials to access attendance.
