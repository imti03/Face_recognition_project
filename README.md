# Face_recognition_project
Certainly, here's a simple README file for the code you've provided:

```markdown
# Face Recognition Attendance System

This is a Python-based Face Recognition Attendance System that captures attendance using a webcam and records it in a CSV file. It utilizes the Face Recognition library and OpenCV for face recognition and image processing.

## Features

- **Training Images:** The system loads known faces and their encodings from a specified folder of training images.
- **Real-time Face Recognition:** The application captures the webcam feed, recognizes faces, and marks attendance for known individuals.
- **Attendance Logging:** The attendance records are logged in a CSV file with timestamps.
- **User-friendly Interface:** You can see the recognized faces and the attendance records in real-time using OpenCV and Streamlit for the web interface.

## Prerequisites

Make sure you have the following libraries and packages installed:

- OpenCV (`cv2`)
- NumPy (`numpy`)
- Face Recognition (`face_recognition`)
- Streamlit (`streamlit`)

You can install these dependencies using `pip`.

```bash
pip install opencv-python numpy face-recognition streamlit
```

## Usage

1. Place images of known faces in the `Training_images` folder, where each subfolder corresponds to a person's name and contains their face images.
2. Run the code. The webcam will open, and the system will start recognizing faces.
3. When a known face is detected, the system will mark attendance in the `Attendance.csv` file. The attendance records will include the person's name and timestamp.
4. To stop the application, press the 'q' key in the webcam window.

## Customization

- You can customize the image directory, CSV file name, and other settings by modifying the code.
