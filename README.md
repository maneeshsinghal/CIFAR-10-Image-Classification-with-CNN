# CIFAR-10 Image Classification with CNN & ROC Analysis 🌟

Welcome to an exciting deep learning journey! 🚀 This project implements
a Convolutional Neural Network (CNN) using TensorFlow/Keras to classify
images from the CIFAR-10 dataset into 10 vibrant classes (e.g.,
airplane, dog, horse). It includes data preprocessing, model training,
ROC curve visualization, sample predictions, and custom image
classification. Let's dive in! 📸

## 📖 Project Overview

This repository contains a complete pipeline for image classification
using the CIFAR-10 dataset. The code is organized into four main
sections:

1.  **CNN Model Training** 🧠: A CNN is built and trained to classify
    CIFAR-10 images with high accuracy.
2.  **ROC Curve Analysis** 📊: Evaluate model performance by plotting
    ROC curves and calculating AUC for each class.
3.  **Sample Visualization** 🖼️: Display one sample image per class with
    true and predicted labels.
4.  **Custom Image Prediction** 🐎: Classify a custom image (e.g.,
    `horse.jpg`) using the trained model.

Powered by **Miracle ⚡**, this project is perfect for learning deep
learning concepts or building upon for advanced computer vision tasks!
😎

## 🎯 Features

-   **Dataset**: CIFAR-10 with 50,000 training and 10,000 test images
    across 10 classes.
-   **Model**: A CNN with convolutional layers, batch normalization, max
    pooling, and a softmax output layer.
-   **Evaluation**: ROC curves with AUC scores for each class to assess
    model performance.
-   **Visualization**: A 2x5 grid of sample images with true and
    predicted labels.
-   **Custom Prediction**: Process and classify custom images (e.g.,
    `horse.jpg`) with ease.
-   **Tech Stack**: TensorFlow, Keras, NumPy, Matplotlib, Scikit-learn,
    OpenCV.

## 🛠️ Installation

To run this project, ensure you have Python 3.x and the required
libraries installed. Follow these steps:

1.  **Clone the Repository**:

    ``` bash
    git clone https://github.com/shervinnd/cifar10-classification.git
    cd cifar10-classification
    ```

2.  **Install Dependencies**:

    ``` bash
    pip install tensorflow numpy matplotlib scikit-learn opencv-python
    ```

3.  **Prepare the Custom Image**:

    -   Place a custom image (e.g., `horse.jpg`) in the project
        directory or update the `img_path` in the code.

4.  **Run the Code**:

    -   Execute the `cifar10.py` script in a Jupyter Notebook or Python
        environment:

        ``` bash
        python cifar10.py
        ```

## 📂 File Structure

-   `cifar10.py`: The main script containing the CNN model, ROC
    analysis, sample visualization, and custom image prediction.
-   `horse.jpg`: Example image for custom prediction (replace with your
    own image).

## 🚀 Usage

1.  **Training the Model**:

    -   The script loads and preprocesses the CIFAR-10 dataset, builds a
        CNN, and trains it for 20 epochs.
    -   Check the model summary and training progress in the console.

2.  **ROC Curve Analysis**:

    -   After training, the script generates ROC curves for each class,
        showing AUC scores for performance evaluation.

3.  **Sample Visualization**:

    -   A 2x5 grid displays one image per class with true and predicted
        labels.

4.  **Custom Image Prediction**:

    -   Replace `horse.jpg` with your image, ensure it's in the correct
        path, and run the script to get the predicted class.

## 📊 Results

-   **Model Performance**: The CNN achieves decent accuracy on CIFAR-10
    after 20 epochs (tune hyperparameters for better results).
-   **ROC Curves**: Visualize model performance with AUC scores per
    class.
-   **Sample Predictions**: See how the model predicts on test set
    samples.
-   **Custom Prediction**: Test the model on any 32x32 RGB image (e.g.,
    `horse.jpg`).

## 💡 Improvements & Future Work

-   Add **data augmentation** to improve model robustness.
-   Implement **dropout** to prevent overfitting.
-   Experiment with advanced architectures like **ResNet** or **VGG**.
-   Enhance custom image preprocessing for better compatibility.
-   Add **model evaluation** on the test set using `model.evaluate`

## 📚 References

-   CIFAR-10 Dataset
-   TensorFlow/Keras Documentation
-   Scikit-learn ROC Metrics

## 🙌 Contributing

Contributions are welcome! 🎉 Feel free to open issues or submit pull
requests to improve the code, add features, or fix bugs. Let's make this
project even better together!

## 📧 Contact

Got questions or ideas? Reach out via GitHub issues 😊

**Powered by Miracle ⚡**
