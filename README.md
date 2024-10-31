

# Insect Detection and Classification Using Convolutional Neural Networks

This repository contains the code, models, and resources for the master’s thesis project **"A Comparison of Convolutional Neural Network Architectures for Insect Detection of Different Sizes"**, completed as part of the Applied Data Science M.Sc. program at Carinthia University of Applied Sciences.

## Project Overview

This study evaluates several Convolutional Neural Network (CNN) models, including YOLOv8, Faster R-CNN, and RetinaNet, to detect and classify insects in high-resolution images. The models were tested for general insect detection and for classification across six insect species, with a specific focus on handling small, occluded, or noisy insect images in natural habitats. This project aims to advance automated methods for ecological monitoring and pest management by exploring model performance in challenging environments.

## Research Goals

The primary objectives of this research include:
- Comparing the precision, F1 score, and mAP of various CNN models for insect detection.
- Investigating model robustness against environmental challenges, such as image noise, occlusion, and varying insect scales.
- Assessing the computational efficiency of models for practical applications in real-time monitoring.

## Methodology

1. **Data Acquisition**: Images were collected from camera traps set up in Carinthia, Austria, using high-resolution Ricoh WG-70 digital cameras. The dataset includes diverse insect species captured under varying environmental conditions.
2. **CNN Architectures**: YOLOv8, Faster R-CNN, and RetinaNet were chosen based on their success in object detection tasks. Each model was trained and evaluated on a labeled insect dataset containing over 1,300 images.
3. **Evaluation Metrics**: Model performance was measured through precision, recall, F1 score, and mean Average Precision (mAP), focusing on both general insect detection and classification at the species level.

## Repository Structure

- **data/**: Contains sample insect images and annotations.
- **models/**: Includes pre-trained models and saved weights.
- **scripts/**: Training, inference, and evaluation scripts for YOLOv8, Faster R-CNN, and RetinaNet models.
- **notebooks/**: Jupyter notebooks used for data analysis and visualization of results.
- **docs/**: Additional project documentation and figures.

## Getting Started

### Prerequisites

- Python 3.11+
- Libraries: PyTorch 2.0.0+cu117, TensorFlow, Detectron2, OpenCV, matplotlib, sklearn

### Results and Analysis

Results are logged in the `results/` directory, with model performance summarized in terms of precision, recall, F1 score, and mAP.

## Key Findings

- YOLOv8 demonstrated superior performance, particularly in small object detection (mAP@50:95 of 0.93177 and F1 score of 0.994).
- Faster R-CNN showed balanced precision and efficiency, ideal for settings where processing speed is critical.
- Environmental challenges, such as image blurriness and occlusions, significantly affected model accuracy.

## Future Work

Future research may involve optimizing model performance for underrepresented insect species and exploring computational cost reductions to facilitate real-time applications.

