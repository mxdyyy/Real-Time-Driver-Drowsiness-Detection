# Real-Time Driver Drowsiness Detection: A Revolution in Road Safety
Welcome to the DorkyDuos team's GitHub repository for our project on Real-Time Driver Drowsiness Detection. This project aims to enhance road safety by employing advanced technologies for real-time detection of driver drowsiness.

This project that focuses on enhancing road safety by using Machine Learning to monitor signs of driver fatigue, such as eye movements and facial expressions, aiming to prevent accidents and reduce road fatalities.
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)

## Team Members
- **Madhav N (Team Leader)**  
  Branch: B.Tech Information Technology
- **Mathangi N**  
  Branch: B.Tech Computer Science Engineering (AI & DS)

## Table of Contents
1. [Introduction](#introduction)
2. [Abstract](#abstract)
3. [Problem Statement](#problem-statement)
4. [Metrics](#metrics)
5. [Tech Stack Used](#tech-stack-used)
6. [Solution](#solution)
7. [Dataset](#dataset)
8. [Working](#working)
9. [Model Architecture](#model-architecture)
10. [Pipeline](#pipeline)
11. [Primary Goals & Statistics](#primary-goals--statistics)
12. [Business Model](#business-model)
13. [Proof of Concept](#proof-of-concept)

## Introduction
Driving fatigue and drowsiness are major contributors to road accidents worldwide. Recognizing the critical need for a proactive approach to enhance road safety, we have developed an advanced system that employs cutting-edge technology for real-time drivers' drowsiness detection.

## Abstract
Our system addresses the pressing issue of driver drowsiness, aiming to mitigate the risks associated with impaired alertness during driving. By utilizing state-of-the-art technologies in computer vision, our solution provides a robust and real-time mechanism to detect signs of drowsiness in drivers.

## Problem Statement
Fatigue reigns as a silent terror on the roads, claiming countless lives yearly. Existing driver monitoring systems, plagued by limitations like inaccuracy and delayed response, fail to effectively combat this threat. We aim to disrupt this paradigm with a groundbreaking system that pinpoints drowsiness with pinpoint accuracy, enabling proactive interventions before tragedy strikes.

## Metrics
1. **Detection Accuracy**: Measuring the system's ability to correctly identify drowsiness in real-time.
2. **False Positive Rate**: Indicates the rate at which the system incorrectly identifies drowsiness when it is not present.
3. **Response Time**: Measures how quickly the system can detect and alert the driver to potential drowsiness.
4. **Precision and Recall**: Precision measures the accuracy of positive predictions, while recall assesses the system's ability to capture all positive instances.
5. **False Negative Rate**: Assesses how often the system fails to detect actual instances of drowsiness.
6. **Robustness**: Performance in diverse environmental conditions (lighting, background noise, etc.).

## Tech Stack Used
- **YOLO (You Only Look Once)**: A real-time object detection system.
- **PyTorch**: A deep learning framework for developing and deploying neural network models.
- **OpenCV**: Used for image processing tasks.
- **Python**: The primary programming language used for development.

## Solution
### Objective of the System
- **Real-time Drowsiness Detection**: Instantly recognizes fatigue signs, enabling immediate intervention.
- **Preventative Measures**: Timely warnings or even car automation can be triggered to avert accidents.
- **Improved Driver Awareness**: Feedback on drowsiness levels can encourage drivers to take breaks or seek rest.
- **Advanced Technologies**: Utilizes machine learning, computer vision, and deep learning to analyze facial expressions, head poses, and eye movements.

## Dataset
To ensure accuracy and effectiveness, we created a custom dataset consisting of images and videos depicting various states of driver alertness. Each action is represented by multiple videos processed into numerous frames.

## Working
1. **Capturing the Driver's Story**: A camera captures the driver's face and head movements in real-time.
2. **Decoding the Drowsiness Clues**: Algorithms track eyelid movements, head nodding, and other subtle behaviors.
3. **Machine Learning Analysis**: A finely tuned object detection model analyzes the pre-processed video stream to detect drowsiness signs.
4. **Feedback and Intervention**: The system provides immediate feedback and escalates interventions as needed.
5. **Continuous Learning**: The system adapts and improves through a continuous feedback loop.

## Model Architecture
1. **Input Video Data**
2. **Data Preprocessing**: Separate preprocessing for awake and drowsy states.
3. **Training and Testing**: The model is trained and tested on the processed data.
4. **Decision Making**: The system makes real-time decisions based on the analysis.
5. **Output**: Generates alerts for drowsy drivers.

## Pipeline
1. Data Acquisition
2. Data Labeling
3. Data Preprocessing
4. Feature Extraction
5. Model Selection
6. Model Training
7. Model Evaluation
8. Real-Time Inference
9. Alert Generation
10. User-Interface Integration
11. Deployment
12. Monitoring and Maintenance

## Primary Goals & Statistics
- **Safety Enhancement**
- **Real-time Vigilance**
- **Feedback Based**
- **Reduce Mishaps**
- **User-Friendly Integration**
- **Adaptive Alerting**
- **Instant Alerts**
- **High Accuracy**
- **Predictive Fatigue Monitoring**

## Business Model
- **Subscription Model**: Offer a subscription-based service to companies and organizations.
- **API Access**: Provide an API and charge a fee based on usage.
- **Data Insights Subscription**: Offer insights and analytics based on collected data.
- **Freemium Model**: Offer a basic version for free with premium upgrades.
- **White Label Solution**: Provide a customizable solution for organizations.

## Proof of Concept
Our system's proof of concept includes live input video footage demonstrating the real-time detection of driver drowsiness.

## Contact
- **Madhav N**: [madhavnarayanan2004@gmail.com](mailto:madhavnarayanan2004@gmail.com)
- **Mathangi N**: [mathanginarayanan2004@gmail.com](mailto:mathanginarayanan2004@gmail.com)
