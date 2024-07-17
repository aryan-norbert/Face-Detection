# Face Detection Project

This project implements real-time face detection using OpenCV and the Haar Cascade classifier in Python, detecting human faces in images and live video feeds from a webcam.

### Methodology:
1. **Preprocessing**: The project loads the Haar Cascade classifier (`haarcascade_frontalface_default.xml`) for detecting frontal faces. Images are preprocessed by converting them to grayscale using OpenCV's `cv2.cvtColor` for efficient face detection.

2. **Detection**: Utilizing the `cv2.CascadeClassifier`, the project identifies faces in images and video frames. Rectangles are drawn around detected faces using `cv2.rectangle`, and results are displayed using `cv2.imshow`.

3. **Real-time Detection**: The project employs a loop to continuously capture frames from the webcam (`cv2.VideoCapture`), detect faces, and display the processed frames in real-time.

### Libraries Used:
- Python 3.x
- OpenCV (cv2): Image and video processing library, including face detection with Haar Cascade classifier.
