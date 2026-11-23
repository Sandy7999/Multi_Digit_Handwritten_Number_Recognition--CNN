# Multi-Digit Handwritten Number Recognition Using CNN and OpenCV

## 📌 Project Overview
This project recognizes handwritten multi-digit numbers from an input image using **Convolutional Neural Network (CNN)** and **OpenCV**.

The CNN model is trained on the MNIST dataset to recognize digits from 0 to 9. OpenCV is used to detect and separate individual digits from the input image. Finally, the model predicts each digit and combines the predictions to display the complete number.

## 🎯 Objectives
- Develop a CNN model for handwritten digit recognition.
- Process handwritten number images using OpenCV.
- Detect and separate individual digits.
- Predict each digit using a trained CNN model.
- Combine the predictions to recognize the complete number.

## 🛠️ Technologies Used
- Python
- Google Colab
- TensorFlow / Keras
- OpenCV
- NumPy
- Matplotlib

## 📂 Dataset
**MNIST Handwritten Digit Dataset**

- Training Images: 60,000
- Testing Images: 10,000
- Image Size: 28 × 28 pixels
- Classes: 0 to 9
- Image Type: Grayscale

Dataset: https://www.tensorflow.org/datasets/catalog/mnist

## 🧠 Model Architecture
The CNN model contains:

1. Input Layer – 28 × 28 image
2. Convolutional Layer – 32 filters
3. Max Pooling Layer
4. Convolutional Layer – 64 filters
5. Max Pooling Layer
6. Flatten Layer
7. Dense Layer – 128 neurons
8. Dropout Layer – 0.3
9. Output Layer – 10 neurons with Softmax

## ⚙️ Working Process
1. Load and preprocess the MNIST dataset.
2. Build and train the CNN model.
3. Upload a handwritten multi-digit number image.
4. Convert the image into grayscale.
5. Use OpenCV to detect and separate individual digits.
6. Resize each digit to 28 × 28 pixels.
7. Predict each digit using the trained CNN model.
8. Combine the predictions to display the complete number.

## 📊 Results

| Evaluation | Result |
|---|---:|
| CNN Test Accuracy | 99.08% |
| Validation Accuracy | 99.23% |
| Detected Digit Regions | 4 |
| Recognized Number | 7934 |

## ▶️ How to Run
1. Open the project notebook in Google Colab.
2. Run all cells in sequence.
3. Wait for the CNN model training to complete.
4. Upload a handwritten number image when prompted.
5. View the detected digits and final recognized number.

## ⚠️ Limitations
- Touching or overlapping digits may not be separated correctly.
- Unclear handwriting can affect prediction.
- Recognition depends on proper image quality and digit spacing.

## 🚀 Future Scope
- Improve recognition of touching digits.
- Support different handwriting styles.
- Develop a web-based handwritten number recognition application.
- Improve image segmentation and prediction accuracy.

- Sandesh Vilas Kondikire 
**Class:** TY B.Tech AI&DS – Division B  
**Academic Year:** 2026–27

## 📚 References
- MNIST Dataset – https://www.tensorflow.org/datasets/catalog/mnist
- TensorFlow Documentation – https://www.tensorflow.org/
- OpenCV Documentation – https://docs.opencv.org/
- Python Documentation – https://docs.python.org/3/
