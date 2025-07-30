# Coral Health Classification using Deep Learning

An automated machine learning system to classify and estimate the lifespan of coral species for coral restoration initiatives using images collected by Autonomous Underwater Vehicles (AUVs).

---

## 🎯 Project Objectives

The primary goal is to create precise and efficient models to classify coral species and estimate their lifespan.
* **Coral Classification**: Implement 2-class and 3-class classification models using Machine Learning and Deep Learning to achieve high accuracy in distinguishing between different coral species.
* **Lifespan Estimation**: Develop models to estimate the lifespan of coral species based on image data.
* **Model Optimization**: Use hyperparameter tuning to enhance the accuracy and efficiency of the models.

---

## 🛠️ Methodology

This project explores several computer vision and machine learning techniques:
* **Deep Learning Architectures**: Convolutional Neural Networks (CNN) and U-Net.
* **Image Analysis**: Object-Based Image Analysis (OBIA).
* **Feature Descriptors**: Bag of Features (BoF), Histogram of Oriented Gradients (HOG), and Local Binary Patterns (LBP).
* **Classifier**: Support Vector Machine (SVM).

---

## 💾 Datasets

The models were trained and evaluated on datasets containing images of healthy, bleached, and dead corals.
* **2-Class Dataset**: Contains 923 images of healthy (438) and bleached (485) corals.
* **3-Class Dataset**: Contains healthy (738), bleached (678), and dead (151) coral images.

---

## 🚀 How to Run

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/Madonis04/Coral-Reef-Classification.git](https://github.com/Madonis04/Coral-Reef-Classification.git)
    cd Coral-Reef-Classification
    ```
2.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
3.  **Run a script:**
    ```bash
    python src/vgg19_classifier.py
    ```
