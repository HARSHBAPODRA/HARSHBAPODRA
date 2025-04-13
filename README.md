# 🎯 Age Detection with OpenCV and Deep Learning

> Original work by [HARSH BAPODRA](https://github.com/HARSHBAPODRA)

## 🚀 Overview
An advanced computer vision system that automatically predicts age from both static images and real-time video streams with impressive accuracy. The system classifies age into convenient brackets (e.g., 15-20 years for teenagers).

## 📋 Requirements
- Python 3.6+
- OpenCV
- imutils
- numpy

## 🧠 How It Works

### Two-Stage Detection Process:
1. **Face Detection** 🎯
   - Locates faces in input images/video
   - Generates precise bounding boxes
   
2. **Age Prediction** 🔮
   - Extracts face Region of Interest (ROI)
   - Applies deep learning model for age prediction

![Age Detection Process](https://github.com/msalmankhaliq/Age-detector/blob/master/opencv_age_detection_examples.jpg)

## 🛠️ Implementation Details

### Face Detection Options:
- **Haar Cascades**: ⚡ Fast, lightweight, good for embedded systems
- **HOG + Linear SVM**: 📊 Better accuracy, slower processing
- **Deep Learning Detectors**: 🎯 Highest accuracy, requires more computing power

### Age Detection Model
![Age Detection Architecture](https://github.com/msalmankhaliq/Age-detector/blob/master/opencv_age_detection_arch.png)

We utilize the pre-trained age detector model by Levi and Hassner, trained on the Adience Dataset (2015). [Learn more here](https://talhassner.github.io/home/publication/2015_CVPR/).

## 📸 Results
![Example Output](https://github.com/msalmankhaliq/Age-detector/blob/master/output.PNG)
*Successfully predicted age range: 8-12 years*

## 📄 License
Licensed under the Apache License, Version 2.0. Copyright 2019.

---
### 🙏 Acknowledgments
Special thanks to [HARSH BAPODRA](https://github.com/HARSHBAPODRA) for the original implementation and inspiration for this project.

### 🤝 Contributing
Feel free to contribute to this project by submitting issues or pull requests.

