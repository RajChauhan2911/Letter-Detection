# 🔤 Handwritten Letter Detection using CNN

## 📌 Overview

This project is a Deep Learning based handwritten letter recognition system built using a Convolutional Neural Network (CNN) in PyTorch.

The model is trained on the **EMNIST Letters Dataset** and can recognize handwritten English alphabets from A–Z.

The notebook allows:
- Training the CNN model
- Evaluating model accuracy
- Uploading custom handwritten letter images
- Predicting the detected letter

---

# 🧠 Features

✅ CNN-based handwritten letter recognition  
✅ Trained on EMNIST dataset  
✅ Deep Learning using PyTorch  
✅ Image preprocessing and normalization  
✅ Real-time custom image prediction  
✅ Model evaluation on test dataset  
✅ Simple and beginner-friendly implementation  

---

# 🛠️ Technologies Used

- Python
- PyTorch
- Torchvision
- NumPy
- Matplotlib
- Pillow (PIL)
- Google Colab

---

# 📂 Dataset

The model uses the **EMNIST Letters Dataset**, which contains handwritten English alphabets.

Dataset details:
- 26 letter classes (A–Z)
- Grayscale images
- Image size: 28×28 pixels

Dataset is automatically downloaded using Torchvision.

---

# 🧱 CNN Architecture

The Convolutional Neural Network includes:

- Convolutional Layers
- ReLU Activation
- Max Pooling
- Fully Connected Layers
- Dropout Regularization

---

# ⚙️ Workflow

## 1️⃣ Data Loading
- Load EMNIST letters dataset
- Apply tensor transformation

## 2️⃣ Model Building
- Create CNN architecture
- Define optimizer and loss function

## 3️⃣ Training
- Train model using Adam optimizer
- Multi-epoch training process

## 4️⃣ Evaluation
- Test model on unseen data
- Calculate accuracy

## 5️⃣ Prediction
- Upload custom handwritten image
- Predict corresponding alphabet

---

# 🎯 Model Accuracy

```text
Test Accuracy: 93.25%
```

The CNN model achieved approximately **93% test accuracy** on the EMNIST letters dataset.

---

# 📸 Sample Output

## Uploaded Image
(Add screenshot here)

## Predicted Letter
```text
Model predicted: A
```

---

# ▶️ How to Run

## Clone Repository

```bash
git clone https://github.com/your-username/letter-detection-cnn.git
```

## Install Dependencies

```bash
pip install torch torchvision matplotlib pillow numpy
```

## Run Notebook

Open the notebook in:
- Google Colab
- Jupyter Notebook

Run all cells sequentially.

---

# 📁 Project Structure

```text
letter-detection-cnn/
│
├── data/
├── handwritten_letter_detection.ipynb
├── README.md
└── sample_images/
```

---

# 🔮 Future Improvements

- Add lowercase letter detection
- Improve prediction accuracy
- Deploy as web application
- Real-time webcam detection
- Support handwritten word recognition
- Add GUI interface

---

# 📚 Learning Outcomes

This project helped in understanding:

- Convolutional Neural Networks (CNN)
- Deep Learning basics
- Image preprocessing
- Handwritten character recognition
- PyTorch workflow
- Model training and evaluation

---

# 👨‍💻 Author

Raj Chauhan

---

# ⭐ GitHub

If you found this project useful, consider giving it a ⭐ on GitHub.
