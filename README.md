# 🧠 Handwritten Digit Classifier using PyTorch

A deep learning project that classifies handwritten digits from the MNIST dataset using a Convolutional Neural Network (CNN) built with PyTorch.

---

## 🎯 Objective

The objective of this project is to develop a Convolutional Neural Network (CNN) using PyTorch to accurately classify handwritten digits (0–9) from the MNIST dataset. The model aims to learn discriminative features of digits through training and evaluate its performance using metrics like accuracy, loss, confusion matrix, and ROC curves.


---
## ✨ Features

- 🔢 Classifies handwritten digits (0–9) using a CNN model
- 🧠 Built from scratch using PyTorch
- 📊 Tracks and plots training & validation accuracy and loss
- 📈 Generates confusion matrix heatmap for performance evaluation
- 📉 Visualizes ROC curves for multi-class classification
- 💾 Supports model saving for future inference
- 🖼️ Displays sample predictions on test images



---
## 🔄 Workflow

The following steps outline the workflow of the handwritten digit classification project:

1. **Data Loading**  
   - Load the MNIST dataset using `torchvision.datasets`.
   - Normalize and transform images using `transforms`.

2. **Model Building**  
   - Define a Convolutional Neural Network (CNN) using PyTorch.
   - Include layers: Conv2D, ReLU, MaxPool, Flatten, Dropout, Fully Connected.

3. **Model Training**  
   - Train the model on the training dataset.
   - Calculate training loss and accuracy per epoch.

4. **Model Validation**  
   - Evaluate performance on the validation set.
   - Plot training and validation accuracy/loss curves.

5. **Performance Evaluation**  
   - Generate confusion matrix and heatmap.
   - Compute ROC curve and AUC scores for multi-class classification.

6. **Prediction**  
   - Predict labels for test images.
   - Display predicted vs actual results for visualization.

7. **Visualization & Reporting**  
   - Save and display plots (accuracy/loss, confusion matrix, ROC).
   - Summarize findings and evaluate model effectiveness.


---


## 📊 Results

The model was evaluated on the MNIST test dataset using several performance metrics. The results are summarized below:

<div align="center">

| Metric              | Value       |
|---------------------|-------------|
| Train Accuracy       | 92.09%      |
| Validation Accuracy | 94.52%      |
| Training Loss       | 0.2356        |
| Validation Loss     | 0.1668        |
| Precision    | 0.9491       |
| Recall    | 0.9486       |
| F1 Score     | 0.9485     |


</div>

---

## 🖼️ Output Images

<div align="center">

<!-- First Row -->
<img src="https://github.com/SayanDhar10/Handwritten-Digit-Classification/blob/2b692f9ba89fba9633bf0e6ff422be92b1d2b7be/Output%20Images/Accuracy%20Curve.png" alt="Accuracy Curve" width="400" style="margin:10px"/>
<img src="https://github.com/SayanDhar10/Handwritten-Digit-Classification/blob/2b692f9ba89fba9633bf0e6ff422be92b1d2b7be/Output%20Images/Confusion%20Matrix.png" alt="Output 2" width="400" style="margin:10px"/>

<br/>

<!-- Second Row -->
<img src="https://github.com/SayanDhar10/Handwritten-Digit-Classification/blob/2b692f9ba89fba9633bf0e6ff422be92b1d2b7be/Output%20Images/Loss%20Curve.png" alt="Loss Curve" width="400" style="margin:10px"/>
<img src="https://github.com/SayanDhar10/Handwritten-Digit-Classification/blob/2b692f9ba89fba9633bf0e6ff422be92b1d2b7be/Output%20Images/ROC%20Curve.png" alt="ROC Curve" width="400" style="margin:10px"/>

<br/>

<!-- Third Row (Single Image Centered) -->
<img src="https://github.com/SayanDhar10/Handwritten-Digit-Classification/blob/2b692f9ba89fba9633bf0e6ff422be92b1d2b7be/Output%20Images/Training%20and%20Validation%20Accuracy.png" alt="Training and Validation Accuracy" width="400" style="margin:10px"/>

</div>

---

### 🔧 Clone the Repository

```bash
git clone https://github.com/SayanDhar10/Handwritten-Digit-Classification.git
cd Handwritten-Digit-Classification



