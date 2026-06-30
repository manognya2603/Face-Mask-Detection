# Face-Mask-Detection
This project uses Deep Learning and Computer Vision to automatically detect whether a person is wearing a face mask. It classifies faces into two categories: Mask and No Mask. The system can process both images and real-time webcam video, making it useful for public health monitoring and access control. 
Features
Detects faces in images and live video.
Classifies each face as Mask or No Mask.
Real-time webcam support.
High-accuracy deep learning model.
Easy-to-use interface.
Displays prediction confidence.
Technologies Used
Python
TensorFlow / Keras
OpenCV
NumPy
Matplotlib
Scikit-learn
Project Structure
Face-Mask-Detection/
│── dataset/
│   ├── with_mask/
│   └── without_mask/
│
│── models/
│   └── mask_detector.h5
│
│── images/
│
│── train_model.py
│── detect_mask_image.py
│── detect_mask_video.py
│── requirements.txt
│── README.md
│── LICENSE
Workflow
Collect and prepare the dataset.
Preprocess and resize the images.
Train a CNN model using TensorFlow/Keras.
Save the trained model.
Detect faces using OpenCV.
Predict whether each detected face has a mask.
Display the result with a bounding box and confidence score.
Skills Demonstrated
Computer Vision
Deep Learning
Image Classification
Model Training
Model Evaluation
Real-time Video Processing
Python Programming
Git & GitHub
