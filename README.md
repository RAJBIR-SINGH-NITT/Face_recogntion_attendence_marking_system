# Face_recogntion_attendence_marking_system
A real-time face recognition attendance system built with Python, OpenCV and dlib. Automatically logs recognized faces into an Excel spreadsheet with timestamps.
# Face Recognition Attendance System 

A Python-based application that uses computer vision to identify individuals in real-time and log their attendance automatically into an Excel database.

## Features
* **Real-time Detection:** Uses OpenCV to stream video and highlight faces with bounding boxes.
* **Instant Recognition:** Matches live frames against a directory of known faces using the 'face_recognition' library.
* **Automated Logging:** Saves the Name, Date, and Time to an '.xlsx' file using 'pandas'.
* **Simple Interface:** Press 'Space' to capture and confirm attendance.

##  Tech Stack
* **Language:** Python 3.x
* **Libraries:** * 'opencv-python' (Image processing)
  * 'face_recognition' (Dlib-based facial feature extraction)
  * 'pandas' & 'openpyxl' (Data management)

# Project Structure
'''text
├── cleaned_faces/        # Folder containing images of known people (Name.jpg)
├── attendance1.xlsx      # Generated attendance log
├── main.py               # Principal logic script
└── README.md
