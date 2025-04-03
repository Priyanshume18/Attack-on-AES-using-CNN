# Attack-on-AES-using-CNN
A project under EEE department, IIT Guwahati

# AES Side-Channel Attack using CNN  

This repository contains Python code for performing a side-channel attack on AES encryption using Convolutional Neural Networks (CNN). The project is part of my research on **AES Hardware Security Architecture with Side-Channel Analysis**. The goal is to analyze power traces from AES implementations and use deep learning techniques to extract secret keys.  

## **Features**  
- **Dataset Handling**: Uses the ASCAD dataset (zero desynchronization).  
- **Preprocessing**: Normalization and feature extraction from power traces.  
- **Deep Learning Model**: A CNN-based architecture designed for key extraction.  
- **Training & Evaluation**: ITrained model with the dataset. 
- **Visualization**: Attack success rates, and key recovery analysis.  

## **Requirements**  
- **Dataset**: Upload the ASCAD dataset (with zero desynchronization).  
- **Python Version**: Latest Python **3.12.4**  
- **Dependencies**:  
  ```bash
  pip install numpy tensorflow pandas matplotlib scikit-learn
