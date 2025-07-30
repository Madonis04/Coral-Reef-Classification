# Coral Health Classification using Deep Learning

[cite_start]An automated machine learning system to classify and estimate the lifespan of coral species for coral restoration initiatives using images collected by Autonomous Underwater Vehicles (AUVs)[cite: 195].

![SVM Diagram](https://i.imgur.com/K3bU2rV.png)

---

## 🎯 Project Objectives

[cite_start]The primary goal is to create precise and efficient models to classify coral species and estimate their lifespan[cite: 198].
* [cite_start]**Coral Classification**: Implement 2-class and 3-class classification models using Machine Learning and Deep Learning to achieve high accuracy in distinguishing between different coral species[cite: 201, 202].
* [cite_start]**Lifespan Estimation**: Develop models to estimate the lifespan of coral species based on image data[cite: 205].
* [cite_start]**Model Optimization**: Use hyperparameter tuning to enhance the accuracy and efficiency of the models[cite: 209].

---

## 🛠️ Methodology

This project explores several computer vision and machine learning techniques:
* [cite_start]**Deep Learning Architectures**: Convolutional Neural Networks (CNN) [cite: 52] [cite_start]and U-Net[cite: 65].
* [cite_start]**Image Analysis**: Object-Based Image Analysis (OBIA)[cite: 80].
* [cite_start]**Feature Descriptors**: Bag of Features (BoF) [cite: 100][cite_start], Histogram of Oriented Gradients (HOG) [cite: 119][cite_start], and Local Binary Patterns (LBP)[cite: 138].
* [cite_start]**Classifier**: Support Vector Machine (SVM)[cite: 147].

---

## 💾 Datasets

[cite_start]The models were trained and evaluated on datasets containing images of healthy, bleached, and dead corals[cite: 217, 221].
* [cite_start]**2-Class Dataset**: Contains 923 images of healthy (438) and bleached (485) corals[cite: 217, 218].
* [cite_start]**3-Class Dataset**: Contains healthy (738), bleached (678), and dead (151) coral images[cite: 221].

---

## 🚀 How to Run

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/YOUR-USERNAME/Coral-Reef-Classification.git](https://github.com/YOUR-USERNAME/Coral-Reef-Classification.git)
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