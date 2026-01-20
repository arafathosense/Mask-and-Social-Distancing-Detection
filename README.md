# 😷 Mask and Social Distancing Detection

The **Mask and Social Distancing Detection** project is a computer vision–based system designed to automatically detect:

* Whether a person is **wearing a face mask or not**
* Whether **social distancing rules** are being maintained in public spaces

The system uses **Deep Learning** and **Object Detection techniques** to analyze images or video streams in real time. This project is particularly relevant for **public safety monitoring**, **crowd management**, and **smart surveillance systems**.



## 🎯 Objectives

* Detect people in images or video streams
* Classify face mask usage (Mask / No Mask)
* Measure distance between individuals
* Identify social distancing violations
* Visualize results in real time with bounding boxes and alerts



## 🧠 System Components

The project consists of two main modules:

### 1️⃣ Face Mask Detection

* Detects human faces
* Classifies each face as:

  * Mask
  * No Mask

### 2️⃣ Social Distancing Detection

* Detects people in a scene
* Computes pairwise distances between detected individuals
* Flags violations when distance falls below a predefined threshold



## 🗂️ Dataset Description

### Face Mask Dataset

* Images of people wearing masks and without masks
* Labeled into:

  * `mask`
  * `no_mask`

### Social Distancing Dataset

* Person detection dataset (e.g., COCO-style format)
* Used for identifying humans in crowded scenes

> ⚠️ Dataset sources depend on implementation. If using a public dataset, please cite the original source.



## 🧠 Model Architecture

### Face Mask Detection

* Convolutional Neural Network (CNN)
* Transfer learning models (optional):

  * MobileNetV2
  * ResNet
  * VGG16

### Social Distancing Detection

* Object Detection Model:

  * YOLO (v3 / v4 / v5)
  * SSD
  * Faster R-CNN
* Euclidean distance calculation between detected centroids



## 🛠️ Technologies Used

* **Programming Language:** Python
* **Libraries & Frameworks:**

  * TensorFlow / Keras
  * OpenCV
  * NumPy
  * Scikit-learn
  * imutils
* **Deep Learning Models:** CNN, YOLO (optional)


## 📊 Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix (for mask detection)

> Performance varies based on dataset quality, lighting conditions, and camera angle.


## 📈 Results

The system successfully:

* Detects face masks in real time
* Identifies unsafe crowd distances
* Works on live webcam and recorded videos

Exact accuracy depends on:

* Model choice
* Training data
* Environmental conditions

<img width="821" height="499" alt="image" src="https://github.com/user-attachments/assets/7e3e706e-e574-4e06-ac4c-6cf7944ccb32" />
<img width="598" height="400" alt="image" src="https://github.com/user-attachments/assets/7a8ca131-c195-4333-9f84-2005a79e9b38" />
<img width="598" height="400" alt="image" src="https://github.com/user-attachments/assets/9d984439-fdbf-4005-a135-50782d4b7773" />
<img width="257" height="251" alt="image" src="https://github.com/user-attachments/assets/74557ff0-fa62-44b4-b7e6-6de9e6bc1061" />
<img width="598" height="400" alt="image" src="https://github.com/user-attachments/assets/fab61b96-a598-44ad-b298-272cbb436cd3" />

## ⚠️ Limitations

* Reduced accuracy in low-light environments
* Occluded faces may affect mask detection
* Distance estimation is camera-angle dependent
* Not a medical-grade or law-enforcement system


## 🔮 Future Enhancements

* Add face recognition for identity tracking
* Improve distance estimation using depth sensors
* Deploy as a web-based surveillance dashboard
* Integrate alert notification system
* Optimize for edge devices (Raspberry Pi, Jetson Nano)

## 👤 Author

**HOSEN ARAFAT**  

**Software Engineer, China**  

**GitHub:** https://github.com/arafathosense

**Researcher: Artificial Intelligence, Machine Learning, Deep Learning, Computer Vision, Image Processing**
