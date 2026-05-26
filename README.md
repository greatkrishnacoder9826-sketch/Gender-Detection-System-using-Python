Gender Detection System using Python

A real-time Gender Detection System built with Python, OpenCV, and Deep Learning models. This project detects human faces through a webcam and predicts gender using computer vision techniques.

Features
Real-time face detection using webcam
Gender prediction (Male/Female)
Haar Cascade face detection
Deep Learning based gender classification
Live camera feed processing
Performance statistics tracking
FPS monitoring
Easy setup and execution
Technologies Used
Python
OpenCV
NumPy
Matplotlib
Dlib
Deep Learning Models (Caffe)
Project Structure
├── models/
│   ├── gender_deploy.prototxt
│   ├── gender_net.caffemodel
│   ├── opencv_face_detector.pbtxt
│   └── opencv_face_detector_uint8.pb
├── gender_detection.ipynb
└── README.md
Installation
1. Clone the Repository
git clone <your-repository-url>
cd gender-detection-system
2. Install Required Libraries
pip install opencv-python numpy matplotlib dlib
Usage
Run the Notebook

Open the Jupyter Notebook:

jupyter notebook

Then run all cells in the notebook.

Webcam Controls
Press Q to quit the live camera feed.
How It Works
Webcam captures live video frames.
OpenCV detects faces in each frame.
Deep Learning model classifies detected faces.
Gender prediction is displayed on screen in real-time.
Models Used
Face Detection
Haar Cascade Classifier
OpenCV DNN Face Detector
Gender Classification
Pre-trained Caffe Deep Learning Model
Performance Metrics

The project also includes:

Face detection count
Gender statistics
FPS calculation
Real-time performance tracking
Example Output
Gender: Male
Confidence: 95%
Future Improvements
Age detection integration
Emotion recognition
Multiple face tracking
Better UI design
GPU acceleration support
Requirements
Python 3.x
Webcam
Jupyter Notebook
Author

Krishna Great

License

This project is open-source and available under the MIT License.
