### **Project README: Layered CNN for Binary Image Classification**

This repository showcases a deep learning project that tackles binary image classification using a custom-built Convolutional Neural Network (CNN). The model is designed to differentiate between "Real" and "Fake" images, using the **140k-real-and-fake-faces** dataset from Kaggle to demonstrate a robust and effective approach to a common computer vision problem.

---

### **Project Highlights**

* **Custom-Built CNN Architecture**: Unlike a transfer learning approach, this project features a CNN designed from scratch. The model is built sequentially, employing multiple `Conv2D` and `MaxPooling2D` layers to effectively learn and extract hierarchical features from images. This showcases a solid understanding of fundamental deep learning principles.

* **Exceptional Performance**: After training on a substantial dataset of **140,000 images**, the model achieved an outstanding **98.3% accuracy** on the test set. This high level of performance underscores the model's ability to generalize well to unseen data.

* **Robust Training & Optimization**: The network is trained with a focus on stability and generalization. It incorporates `BatchNormalization` to stabilize learning and `Dropout` layers to prevent overfitting, ensuring the model's reliability in a real-world application.

* **Comprehensive Code & Visualizations**: The repository includes the full code for building, training, and evaluating the model. You'll also find visualizations of training and validation metrics, such as accuracy and loss plots, which provide valuable insight into the model's learning process.

---

### **Technology Stack**

* **Core Libraries**: `TensorFlow`, `Keras`
* **Data Handling**: `ImageDataGenerator`
* **Numerical Operations**: `NumPy`
* **Visualization**: `Matplotlib`

### **Dataset**

The model was trained and validated using the `140k-real-and-fake-faces` dataset, available on Kaggle:

[**140k Real and Fake Faces Dataset**](https://www.kaggle.com/datasets/xhlulu/140k-real-and-fake-faces)

This project serves as an excellent resource for anyone looking to understand the mechanics of building a deep learning model for image classification from the ground up, highlighting best practices for achieving high accuracy and preventing common training issues.
