# FaceRecPy

**FaceRecPy** is a simple facial detection project using Python, OpenCV, Mediapipe, and the CVZone library. This project captures real-time images using the webcam and detects faces in the video, displaying the results in a window.

## Technologies Used

- **Python 3.9**
- **OpenCV** (`opencv-python`)
- **Mediapipe**
- **CVZone**

## Prerequisites

Before running the project, you will need to install the dependencies. It is recommended to use a virtual environment (such as `venv` or `virtualenv`).

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/FaceRecPy.git
   ```

2. Create and activate a virtual environment (optional, but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # For Linux/Mac
   .\venv\Scripts\activate  # For Windows
   ```

3. Install the project dependencies:
   ```bash
   pip install opencv-python mediapipe cvzone
   ```

## How to Run the Project

After installing the dependencies, you can run the main script to start facial detection:

```bash
python main.py
```

The script will open the webcam and start detecting faces in real-time. To stop the program, just press the **Esc** key.

## Project Features

- **Real-Time Facial Detection:** The project captures the webcam feed and uses CVZone's face detector to identify and highlight faces in the video.
- **Simple Interaction:** The video with face detection is displayed in a window, and the program can be closed by pressing the **Esc** key.

#

> You can use this code as a foundation to expand your idea, if you need to implement features like facial recognition, emotion detection, or other computer vision-related applications.

