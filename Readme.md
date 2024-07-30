# Face Detection Project

## Description
This project uses OpenCV to detect faces in real-time video feed from a webcam.

## Installation
- Install OpenCV using pip: `pip install opencv-python`
- Clone this repository: `git clone https://github.com/your-username/face-detection.git`
- Run the script using Python: `python main.py`
- Press 'q' to quit the program

## How it works
- The script loads the CascadeClassifier for face detection from the OpenCV library.
- It captures video feed from the default webcam (index 0).
- For each frame, it converts the image to grayscale and detects faces using the detectMultiScale method.
- It draws rectangles around the detected faces using the rectangle method.
- It displays the output in a window titled "Face Detection".

## Notes
- This project uses the default frontal face detection model provided by OpenCV. You can experiment with other models or train your own model for better accuracy.
- This project assumes that the webcam is installed and working properly. If you encounter issues with video capture, check your webcam settings and ensure that it is properly installed.

## Contributing
Contributions are welcome! Please submit a pull request with your changes and a brief description of what you've added or fixed.