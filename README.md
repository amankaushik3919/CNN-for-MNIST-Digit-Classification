# DNN-for-MNIST-Digit-Classification


# 🧮 Digit Recognition using Convolutional Neural Networks (CNN)

Welcome to my GitHub repository! This project demonstrates how to use a Convolutional Neural Network (CNN) to perform handwritten digit recognition using the MNIST dataset.

## 📌 Project Overview

This notebook builds, trains, and evaluates a CNN model using TensorFlow and Keras. It classifies grayscale 28x28 pixel images of digits (0 through 9) from the popular MNIST dataset.

## 🔧 Technologies Used

- Python 3.x
- TensorFlow 2.x
- Keras (with TensorFlow backend)
- NumPy
- Matplotlib (for visualization)
- Jupyter Notebook

## 📁 Dataset

- **MNIST Dataset**: 60,000 training images and 10,000 test images of handwritten digits.
- Dataset is automatically downloaded using Keras datasets API.

## 🧱 Model Architecture

```
Input Layer: 28x28 grayscale image
→ Conv2D (32 filters, 3x3) + ReLU
→ MaxPooling2D (2x2)
→ Conv2D (64 filters, 3x3) + ReLU
→ MaxPooling2D (2x2)
→ Flatten
→ Dense (64 units) + ReLU
→ Output Layer (10 units with Softmax)
```

## 🚀 How to Run

1. **Clone the repository**:

```bash
git clone https://github.com/your-username/digit-recognition-cnn.git
cd digit-recognition-cnn
```

2. **Install dependencies**:

Make sure you have Python and pip installed.

```bash
pip install tensorflow numpy matplotlib
```

3. **Run the Notebook**:

Launch Jupyter or VSCode and open `Digit-RecognitionCNN.ipynb` to run the code step by step.

## 📈 Training Results

- Achieved over **98% accuracy** on test data.
- Visualizations include sample predictions to verify model performance.

## 🖼️ Sample Output

Example of visualized predictions:
- Correct predictions: ✅
- Incorrect predictions: ❌

## 📚 Learning Outcome

This project helps understand how CNNs work for image classification tasks and the importance of preprocessing and architecture tuning.

## 💡 Future Enhancements

- Use dropout or batch normalization to reduce overfitting.
- Explore deeper or more complex architectures.
- Try training on a custom handwritten digit dataset.

## 📝 License

This project is open source and unlicensed.

---

**Developed with ❤️ and Python.**
