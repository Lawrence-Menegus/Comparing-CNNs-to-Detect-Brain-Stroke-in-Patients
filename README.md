# Brain Stroke Detection Using CNN (Convolutional Neural Networks) with Keras and PyTorch

### Overview
<p> This project aims to conduct a comprehensive analysis of brain stroke detection using Convolutional Neural Networks (CNN). Two datasets consisting of brain CT images were utilized for training and testing the CNN models. The objective is to accurately classify CT scans as exhibiting signs of a stroke or not, achieving high accuracy in stroke detection based on radiological imaging.</p>

### Project Objective
<p> The primary objective of this project is to develop and compare two CNN models using PyTorch and Keras for the classification of brain CT images into normal and stroke categories. </p>

### Data Sources
<p> The datasets used in this project were obtained from Kaggle. Specifically, the Brain Stroke CT Image Dataset by afridirahman was utilized. </p>

### Data Processing
<p> Cleaning and Preprocessing: 
The datasets were processed to resize, convert to RGB, and normalize the images before feeding them into the models. </p>

### Dataset Splitting
<p> The data was split into training and testing sets using a 90-10 ratio.</p>

### Model Building
<p> CNN Model with PyTorch
A Binary Classifier CNN model was built using PyTorch, consisting of convolutional layers, max-pooling, dropout layers, and fully connected layers. </p>

### CNN Model with Keras
<p> A similar Binary Classifier CNN model was constructed using Keras, with convolutional layers, max-pooling, dropout layers, and dense layers. </p>

### Model Evaluation
<p> Training and Testing: 
Both models were trained using the training data and evaluated using the testing data. Training metrics such as loss and accuracy were monitored. </p>

### Performance Metrics
<p> Performance metrics including accuracy, precision, recall, and the confusion matrix were calculated to assess the models' performance.</p>


### Results Visualization
<p> Precision-Recall Curve: 
Precision-Recall curves were plotted to visualize the trade-off between precision and recall for both models. </p>

### Confusion Matrix
<p> Confusion matrices were generated to visualize the classification performance of the models. </p>

### Image Predictions
<p> Sample CT scan images with their actual and predicted labels were displayed to illustrate the models' predictions. </p>

### References
<p> Kaggle Dataset: Brain Stroke CT Image Dataset - afridirahma </p>


## Contributor 
<p>Lawrence Menegus</p>