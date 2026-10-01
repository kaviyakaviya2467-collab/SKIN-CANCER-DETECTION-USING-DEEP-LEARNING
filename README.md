# SKIN-CANCER-DETECTION-USING-DEEP-LEARNING

Absolutely. I studied your **Deep Learning Project notebook**. Based on the actual project content, here is a clean **README.md** you can add to GitHub and then share the repository on LinkedIn.

#  Skin Cancer Detection Using Deep Learning

##  Project Overview

This project develops a **deep learning-based skin cancer detection system** using dermoscopic skin lesion images. The objective is to classify skin lesions into **Benign** and **Malignant** categories using CNN-based models.

Three deep learning approaches were implemented and compared:

* **CNN**
* **VGG16**
* **MobileNetV2**

The models were evaluated using test accuracy, loss, classification reports, and confusion matrices.

##  Project Objective

The main objective is to build a deep learning model that can automatically classify skin lesion images as **Benign or Malignant** and explore different CNN architectures for image classification.

##  Dataset

The project uses a **Melanoma Skin Cancer Dataset** containing dermoscopic images of skin lesions.

### Classes

* **Benign — 0**
* **Malignant — 1**

The dataset is divided into training and testing data and is used for supervised image classification.

##  Technologies & Libraries

* Python
* TensorFlow
* Keras
* NumPy
* Pandas
* Matplotlib
* Seaborn
* OpenCV
* Scikit-learn

##  Models Used

### 1. CNN

A custom Convolutional Neural Network was developed using convolution, pooling, dense, and dropout layers to extract features from skin lesion images.

**Test Accuracy:** 90.1%

### 2. VGG16

VGG16 with pre-trained ImageNet weights was used for feature extraction and binary classification.

**Test Accuracy:** 87.9%

### 3. MobileNetV2

MobileNetV2 was used as a lightweight pre-trained CNN architecture for efficient feature extraction and classification.

**Test Accuracy:** **91.2%**

##  Model Comparison

| Model       | Test Accuracy |  Test Loss |
| ----------- | ------------: | ---------: |
| CNN         |         90.1% |     0.2242 |
| VGG16       |         87.9% |     0.2776 |
| MobileNetV2 |     **91.2%** | **0.2165** |

MobileNetV2 achieved the highest test accuracy among the three models evaluated in this project.

##  Evaluation Metrics

The models were evaluated using:

* Accuracy
* Loss
* Precision
* Recall
* F1-Score
* Confusion Matrix
* Classification Report

For MobileNetV2, the classification report showed approximately **0.91 precision, recall, and F1-score** across the two classes.

##  Key Learning Outcomes

* Image preprocessing for deep learning
* Exploratory analysis of image datasets
* CNN architecture development
* Transfer learning using VGG16 and MobileNetV2
* Model training and validation
* Performance evaluation
* Model comparison
* Binary image classification

##  Conclusion

This project demonstrates the application of deep learning techniques for **melanoma skin lesion classification**. CNN, VGG16, and MobileNetV2 were trained and evaluated, with MobileNetV2 achieving the highest test accuracy of **91.2%** on the evaluated test set.

The project provided practical experience in **computer vision, CNNs, transfer learning, image preprocessing, and deep learning model evaluation**.

> **Note:** This project is intended for educational and research purposes and is not a substitute for professional medical diagnosis.

## 👩‍💻 Project Skills

**Python | Deep Learning | CNN | TensorFlow | Keras | Computer Vision | Transfer Learning | VGG16 | MobileNetV2 | Image Classification | Data Visualization**
