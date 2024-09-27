# ships-classification
Ship Classification in Port Environments
Project Overview
This project focuses on the automatic classification of ship images captured in port environments. The system aims to improve real-time monitoring of maritime operations, assisting in the efficient management and safety of ports. The complex task of identifying and categorizing ships is addressed using advanced deep learning techniques, specifically Convolutional Neural Networks (CNN).

Problem Statement
Managing maritime ports involves monitoring and classifying ships based on various characteristics such as type, size, and condition. This process is often prone to human error, especially in challenging weather conditions or overcrowded ports. The goal of this project is to create a system that automates the classification of ships, enhancing port management and operational efficiency.

Objectives
Develop a system to automatically classify ships using image data from maritime ports.
Utilize deep learning techniques, particularly CNNs, to analyze ship characteristics.
Improve port logistics and security by providing accurate real-time information about incoming and outgoing vessels.
Methodology
Dataset
We utilized the "Game of Deep Learning Ship" dataset, which consists of 8,932 images of five ship categories: Cargo, Military, Carrier, Cruise, and Tanker. The dataset was pre-processed to balance class distribution, and various data augmentation techniques were applied, including image resizing, flipping, and color adjustments.

Models
The following CNN architectures were evaluated:

Inception
Xception
VGG
ResNet50
ResNet152
Best Model
The ResNet152 model achieved the highest accuracy of 91% across all classes. It demonstrated superior classification performance, particularly with 95% accuracy for the "Carrier" class and 93% for "Tankers."

Evaluation
Key metrics used for evaluation include:

Accuracy
Precision
Recall
F1-Score
The ResNet152 model outperformed other models in all metrics, highlighting its robustness in various port scenarios.

Results
Overall Accuracy: 91%
Class-wise Accuracy:
Cargo: 81%
Military: 92%
Carrier: 95%
Cruise: 92%
Tankers: 93%
Conclusion
This project successfully implemented a ship classification system using CNNs. The ResNet152 model, in particular, showed outstanding performance, providing reliable ship classifications under various environmental conditions. Future work can explore further optimization of the model and its deployment in real-world port management systems.
