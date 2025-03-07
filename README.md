# Insect Detection and Classification Using Convolutional Neural Networks  

This repository contains the code, models, and resources for the master's thesis project:  

**"A Comparison of Convolutional Neural Network Architectures for Insect Detection of Different Sizes"**  

📌 **Author**: Saghar Ghaffari, B.Sc.  
📌 **Degree**: Master of Science (M.Sc.), Applied Data Science  
📌 **Institution**: Carinthia University of Applied Sciences  
📌 **Supervisors**:  
- FH-PROF. DR.-ING. Karl-Heinrich Anders  
- FH-PROF. DIPL.-ING. DR. TECHN. Adrijana Car  

## 📌 Project Overview  
This study evaluates and compares the performance of three Convolutional Neural Network (CNN) models:  
- **YOLOv8**  
- **Faster R-CNN**  
- **RetinaNet**  

These models were tested for **insect detection and classification** across six species using high-resolution images. The goal is to improve **ecological monitoring** and **pest management** by identifying the most effective CNN architecture for challenging real-world conditions (e.g., small insects, occlusions, and noisy environments).  

## 🎯 Research Goals  
✔️ Compare **precision, F1 score, and mAP** across different CNN models.  
✔️ Analyze robustness against **environmental challenges** (e.g., occlusions, background noise, varying insect sizes).  
✔️ Assess **computational efficiency** for real-time monitoring applications.  

## 🛠️ Methodology  
1. **Data Acquisition**  
   - High-resolution images collected via **Ricoh WG-70** digital cameras.  
   - Camera traps deployed in **Carinthia, Austria** (various natural habitats).  

2. **Model Selection**  
   - **YOLOv8**, **Faster R-CNN**, and **RetinaNet** trained on a dataset of **1,300+ labeled images**.  

3. **Evaluation Metrics**  
   - **Precision, Recall, F1-score, and Mean Average Precision (mAP)** assessed at both **insect-level and species-level detection**.  

## 📂 Repository Structure  

Master-Thesis/ 

│── data/ # Sample insect images and annotations
│── models/ # Pre-trained models and saved weights

│── scripts/ # Training, inference, and evaluation scripts

│── notebooks/ # Jupyter notebooks for analysis & visualization

│── results/ # Performance metrics & final model outputs

│── docs/ # Additional documentation and figures

│── thesis.pdf # Full Master Thesis document

│── README.md # Project documentation

│── .gitignore # Ignore unnecessary files

│── LICENSE # Open-source license
