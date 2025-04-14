# A General-Use Neural Network for Extracting Patterns from Images

This repository contains everything you need to train and predict patterns in images, as well as a web app for preparing training data and visualizing results.

## Current Use Case
The neural network is currently trained on images of islands surrounded by the sea, identifying:
- **Upper border:** Often trees or foliage.
- **Bottom border:** Beaches or shorelines.

However, this versatile model can be trained on virtually any set of images with a common feature, such as:
- Eye shapes
- Facial expressions
- Highway traffic signs

The training is done via the web app by drawing lines around the pattern to be detected.

---

## Example
1. **Input image**
![Screenshot (411)](https://github.com/user-attachments/assets/610cfcbf-5c57-4563-8217-ba663ca9a1af)

2. **Output coordinates over the input image and the UI**
![Screenshot 2024-12-05 044835](https://github.com/user-attachments/assets/a6b9e887-9684-462f-8e52-ed38c4e9baba)
Note the shallow water area.

## Repository Contents
1. **Frontend Web App**  
   - Built with **React.js** and **JavaScript**  
   - Prepare training datasets and display prediction results.

2. **Backend Neural Network**  
   - Developed in **C++** using **LibTorch** (PyTorch equivalent).  
   - Includes training and prediction algorithms.

3. **Example Implementation**  
   - Pre-trained models.  
   - Training data and prediction results.  
   - Executable files for custom implementations.

---

## Setup Requirements
To get started, ensure you have:  
- **Windows 10 SDK, version 1903 (10.0.18362.1):** [Download here](https://developer.microsoft.com/en-us/windows/downloads/sdk-archive)

---

## Additional Resources
Download the backend files and pre-trained models from Google Drive:  
[Google Drive Link](https://drive.google.com/drive/folders/1hlLvVV1VnTB9Lspz-FuoH1UQoHWP2dg_?usp=sharing)
