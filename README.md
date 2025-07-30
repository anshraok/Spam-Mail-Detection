# Spam-Mail-Detection


This project is a deep learning-based system to classify emails as **Spam** or **Ham (Not Spam)**. It uses modern NLP techniques, including embedding, preprocessing, and a neural network classifier to distinguish between spam and legitimate messages with high accuracy.

---

## 🚀 Features

- 🔤 Preprocesses raw email text (tokenization, stopword removal, padding)
- 🧠 Utilizes **MCP (Multi-Class Perceptron)** architecture
- 📊 Trains on labeled spam/ham email datasets
- 🔍 Performs inference on real-world email samples
- 📈 Achieves high accuracy and low false positive rate

---

## 🧠 Model Architecture

- Embedding Layer (optional for advanced variants)
- MCP (Multi-Class Perceptron) classifier
- Activation: ReLU or Sigmoid
- Loss: Binary Cross Entropy
- Optimizer: Adam

---

## 📁 Dataset

- Used a labeled email dataset with `text` and `label` columns.
- Labels:
  - `1` → Spam  
  - `0` → Ham (Not spam)

Popular datasets used:
- [SMS Spam Collection](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)
- [Enron Email Dataset](https://www.kaggle.com/wcukierski/enron-email-dataset)

---

## 🛠️ Technologies Used

| Tool/Library | Purpose                      |
|--------------|------------------------------|
| Python       | Core programming language    |
| TensorFlow / Keras | Model building &
