## README

### CIFAR-10 Image Classification: ANN vs CNN

**Project Overview**
This notebook compares the performance of Artificial Neural Networks (ANNs) and Convolutional Neural Networks (CNNs) in classifying images from the CIFAR-10 dataset. The goal is to demonstrate the superiority of CNNs for image-based tasks.

**Dataset**
The CIFAR-10 dataset, consisting of 60,000 32x32 color images in 10 classes, is used for training and testing.

**Methodology**
1. **Data Preparation:** The dataset is loaded and preprocessed.
2. **ANN Model:** An ANN model is created and trained on the dataset.
3. **CNN Model:** A CNN model is created and trained on the dataset.
4. **Model Evaluation:** Both models are evaluated on a test set using metrics like accuracy, precision, recall, and F1-score.
5. **Model Comparison:** A visual comparison of the models' performance is presented through graphs.
6. **Prediction Function:** A function is implemented to predict the class of a given image.

**Results**
The CNN significantly outperforms the ANN, achieving a weighted average F1-score of 0.70 compared to 0.46 for the ANN on a test set of 10,000 images. This highlights the effectiveness of CNNs in capturing spatial features in images.

**Dependencies**
* TensorFlow/Keras
* NumPy
* Matplotlib (for visualization)

**Note:** This README will be updated as the project progresses.

**Additional Information**
* Detailed explanations and comments are included within the Jupyter Notebook.
* Hyperparameters and configuration details are documented.

