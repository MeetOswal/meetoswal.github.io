---
title: "HoopTrack: Real-Time Basketball Trajectory Prediction Using Computer Vision"
excerpt: " The aim of this project is to develop a computer vision system that can predict the path of a basketball from a video sequence. This system does not use deep learning techniques, focusing instead on traditional computer vision methods."
collection: portfolio
---
Objective
------
Develop a system to predict basketball paths from videos using traditional computer vision methods.

**Aim**: 
- Detect the basketball in video frames. 
- Track the basketball's movement across frames. 
- Predict the future path based on movement data.

**Implementation**:
- Video Frame Extraction: Utilize cv2.VideoCapture to read video files and individual frames saved as JPEG images for further processing. 
- Object Detection via Template Matching: Employ cv2.matchTemplate with the basketball template. Matches with correlation coefficients above 0.81 are considered successful detections. 
- Trajectory Tracking: Record the center points of detected basketball positions across frames. 
Prediction: Fit a quadratic polynomial to trajectory points to estimate future path. 
- Visualization: Plot and save trajectory on each frame. 
Video Compilation: Assemble processed frames back into a video using cv2.VideoWriter. 
- Final Output: A video showing the basketball’s detected and predicted path. 
- Tools and Libraries: OpenCV for image processing, NumPy for numerical operations, Matplotlib for plotting.

**Result**:
<br/><img src='/files/cv.jpg'>

Keywords
------
Computer Vision, Machine Learning, Python, Template Matching. 