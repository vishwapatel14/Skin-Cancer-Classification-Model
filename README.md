# Skin Cancer Classification Model for Advanced Machine Learning Course

## **Overview**
Skin cancer is one of the most prevalent cancers globally, and early detection significantly improves prognosis. This project aims to develop a machine learning pipeline for binary classification of skin lesions (cancerous vs. noncancerous) and explain the predictions using state-of-the-art interpretability techniques like **Integrated Gradients** and **Guided Grad-CAM** (via Captum). The goal is to provide a model that is not only accurate but also trustworthy for real-world healthcare applications.

---

## **Key Features**
- **Deep Learning Model**: A convolutional neural network (CNN) trained on the ISIC dataset.
- **Hybrid Approach**: Outputs from the CNN's dense layer are used as inputs for additional classifiers in a Mixture of Experts model.
- **Interpretability**: Attribution overlays generated using **Captum** to explain predictions.
- **Class Imbalance Handling**: Techniques to address the significant imbalance between cancerous and noncancerous samples in the dataset.

---

## **Dataset**
The dataset for this project is from the 2024 ISIC Competition on Kaggle, which can be found here: 
https://www.kaggle.com/competitions/isic-2024-challenge/data

