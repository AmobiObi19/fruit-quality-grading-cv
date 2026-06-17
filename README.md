## Fruit Quality Grading Using Computer Vision
Overview

This project presents a computer vision-based system for automated fruit quality assessment using deep learning. The objective is to classify fruits as fresh or defective and provide visual explanations of model predictions using Grad-CAM.

# Objectives
- Develop an automated fruit quality grading system
- Classify fresh and defective fruits using deep learning
- Improve quality control efficiency in agricultural production
- Enhance model transparency through Explainable AI (XAI)
# Dataset
The dataset consists of images of fresh and defective fruits, including:
- Apple
- Banana
- Orange
- Tomato
- Potato
- Cucumber
- Okra
Images were organized into multiple quality categories for model training and evaluation.
# Methodology
Model
- MobileNetV2 (Pretrained)
- Transfer Learning
- Fine-tuning for fruit quality classification
- Explainability
- Grad-CAM (Gradient-weighted Class Activation Mapping)
- Visualization of image regions influencing model decisions
# Tools
- Python
- PyTorch
- OpenCV
- NumPy
- Matplotlib
# Performance Results
# Metric	Value
- Accuracy	91.80%
- Precision	91.42%
- Recall	91.11%
- F1-Score	91.26%
# Key Findings
- MobileNetV2 achieved high classification accuracy while remaining computationally efficient.
- Grad-CAM visualizations highlighted relevant fruit regions used during prediction.
- The system demonstrated potential for real-time fruit quality assessment and agricultural quality control.
# Applications
- Smart agriculture
- Food quality inspection
Automated sorting systems
- Post-harvest quality management
# Future Work
- Real-time deployment on edge devices
- Expansion to additional fruit categories
- Integration with mobile and IoT-based agricultural systems
- Advanced explainability techniques
  
# Author
Amobichukwu Obi

