# FakeNewsDetection
This project implements a Fake News Detection model using LSTM (Long Short-Term Memory) in TensorFlow/Keras. It classifies news articles as either real or fake based on textual content.

📌 Steps in the Project:
✔️ Data Preprocessing: Merging real (true.csv) and fake (fake.csv) news datasets with labels.
✔️ Text Tokenization & Padding: Converting text to sequences and padding them for uniform input length.
✔️ Model Architecture:

Embedding layer for word representation
LSTM layer for sequence learning
Dropout for regularization
Dense layer with sigmoid activation for binary classification
✔️ Training & Evaluation: Model is trained for 5 epochs, achieving high accuracy.
🔗 Tech Stack
Python, Pandas, NumPy for data handling
TensorFlow/Keras for LSTM-based classification
Scikit-learn for dataset splitting
