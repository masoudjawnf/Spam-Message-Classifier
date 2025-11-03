# Spam-Message-Classifier
SMS Spam Classifier using Neural Networks

## Spam Message Classifier

This project is an SMS Spam Detection System built using a custom neural network model with TensorFlow and Keras.

### 📋 Overview:
- Uses a CSV dataset containing SMS messages labeled as "spam" or "ham".
- Trains a custom vector embedding model with high accuracy (~98%) to classify spam messages.
- Utilizes layers such as TextVectorization, Embedding, GlobalAveragePooling1D, Flatten, Dense (with ReLU and Sigmoid activation).
- Outputs predictions into a CSV file indicating whether each message is spam or not.

### 🔧 Model Highlights:
- Text preprocessing and tokenization.
- Embedding layer to capture semantic relationships between words.
- Dimensionality reduction with GlobalAveragePooling1D.
- Binary classification with Sigmoid activation.
- Achieves high accuracy on test data.

### 📂 Files:
- `train.csv` → Training dataset
- `test.csv` → Test dataset
- `output.csv` → Model predictions
- `spamREC.py` → Model training & evaluation code
- `README(Farsi).pdf` (in Persian) → Full project report (Persian)

### 🚀 Tools & Technologies:
- Python
- TensorFlow & Keras
- Pandas & Numpy
- Sklearn
- CSV Handling

### 🤝 Contributors
- [MasoudJanfashan](https://github.com/masoudjawnf)
- [SanazAllahyari](https://github.com/Sanaz-all)

