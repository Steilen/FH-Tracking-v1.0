# FH Tracking v1.0

FH (Face and Hand) Tracking v1.0 is a Python application that utilizes MediaPipe's Hands and Face Mesh solutions to track and visualize hand and face landmarks in real-time using a webcam.

## Features

- **Hand Tracking:** Tracks hands and draws landmarks and connections with custom visualization.
- **Face Mesh:** Tracks face landmarks and visualizes the facial mesh, contours, lips, and eyes with customizable styles.
- **Real-time Processing:** Processes webcam input in real-time for smooth tracking.

## Requirements

- Python 3.6 or later
- OpenCV
- MediaPipe

## Installation

1. **Install the required Python packages:**

    ```bash
    pip install opencv-python mediapipe
    ```

## Usage

1. **Run the application:**

    ```bash
    python main.py
    ```

2. The application will open a window displaying the webcam feed with hand and face tracking. Press `q` to exit the application.

## Customization

- **Hand Landmarks:**
  - The color, thickness, and radius of the points and lines connecting hand landmarks can be customized in the code.

- **Face Mesh:**
  - Customize the styles for the face mesh, including tessellation and contours, by modifying the drawing specifications in the code.

## Acknowledgments

- [MediaPipe](https://pypi.org/project/mediapipe/) for the powerful solutions used in this project.
- [OpenCV](https://pypi.org/project/opencv-python/) for image processing and visualization.

