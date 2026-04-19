# Gravitational Wave Signal Classification using Deep Learning (CNN)

## Project Overview

This project focuses on detecting and classifying gravitational wave signals from noisy space data using deep learning. A Convolutional Neural Network (CNN) model is trained on spectrogram images to automatically identify patterns corresponding to different types of gravitational wave signals.

Gravitational waves are ripples in spacetime caused by massive cosmic events such as black hole mergers. Detecting these signals is challenging due to high levels of noise, making this an ideal application for AI.

---

##  Objective

* Build a deep learning model to classify gravitational wave signals
* Automatically distinguish between real signals and noise
* Analyze model performance using multiple evaluation metrics

---

##  Methodology

### 1. Data Preprocessing

* Input data consists of spectrogram images
* Images are resized to a uniform shape (128x128)
* Pixel values are normalized for better training

### 2. Model Architecture

* Convolutional Neural Network (CNN) used for feature extraction
* Multiple Conv2D and MaxPooling layers
* Dropout layer added to prevent overfitting
* Softmax activation for multi-class classification

### 3. Training Process

* Model trained on labeled dataset
* Validation data used to monitor performance
* Early stopping and checkpoints used (if implemented)

### 4. Evaluation Metrics

* Accuracy
* Loss curves
* Confusion Matrix
* ROC / Precision-Recall curves
* Top-K Accuracy

---

## Results & Visualizations

The following visualizations were generated to evaluate the model:

*  Training Accuracy vs Validation Accuracy
*  Training Loss vs Validation Loss
*  Confusion Matrix (Normalized)
*  ROC Curve (Multi-class)
*  Precision-Recall Curve
* Sample Predictions (Correct vs Incorrect)

*(Add screenshots of these graphs in an `images/` folder and link them here)*

##  Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* Matplotlib
* Scikit-learn
## How to Run the Project
### Run on Google Colab
Open the notebook directly:
https://colab.research.google.com/github/Anushka-Pokhriyal/Gravitational-Wave-Signal-Classification/blob/main/Gravitational_Wave_Signal_Classification.ipynb
### Run Locally
1. Clone the repository:
```bash
git clone https://github.com/Anushka-Pokhriyal/Gravitational-Wave-Signal-Classification.git
```
2. Install dependencies:
```bash
pip install tensorflow numpy matplotlib scikit-learn
```
3. Open the notebook:
* Run in Jupyter Notebook or Google Colab
## Key Learnings
* Understanding of CNNs for image classification
* Handling noisy real-world data
* Model evaluation using multiple metrics
* Visualization of model performance
## Future Improvements
* Use Transfer Learning (ResNet, EfficientNet)
* Add Grad-CAM for better interpretability
* Deploy as a web app using Streamlit
* Improve accuracy with hyperparameter tuning
##  Applications

* Detection of black hole collisions
* Space research and astrophysics
* Signal classification in noisy environments

---

##  Author

**Anushka Pokhriyal**

---

##  Acknowledgment

Dataset inspired by gravitational wave detection research (Gravity Spy / Kaggle)
(https://www.kaggle.com/datasets/tentotheminus9/gravity-spy-gravitational-waves)

---
