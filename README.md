# Fake_news_classification
Real-Time Fake News Detection

A deep learning-powered application to detect whether a news article is Real or Fake. This project uses LSTM-based neural networks and pre-trained word embeddings to analyze the content of news articles and predict their authenticity.

Features

Binary Classification: Classifies news articles as Real or Fake.

Pre-trained Word Embeddings: Uses GloVe embeddings to capture semantic meaning of words.

Interactive Web Interface: Built with Gradio for real-time predictions.

Confidence Visualization: Shows a bar chart indicating the model’s confidence in its prediction.

Data Preprocessing: Cleans text and converts it into sequences using Keras Tokenizer.

Train/Test Split: Ensures robust evaluation by splitting data into training, validation, and test sets.

Save & Load Model: The trained model and tokenizer are saved for reuse without retraining.

Spark Integration: Uses PySpark for scalable CSV data handling.

Technologies Used

Python 3

TensorFlow & Keras (for building and training the LSTM model)

NumPy & Pandas (data handling)

Scikit-learn (train-test split, confusion matrix)

Matplotlib & Seaborn (visualization)

GloVe embeddings (pre-trained word vectors)

PySpark (data loading and preprocessing)

Gradio (interactive web interface)

How It Works

Load a dataset containing news articles labeled as real or fake.

Clean and preprocess the text data.

Convert text into sequences using a Keras Tokenizer.

Pad sequences to ensure consistent input length.

Build an LSTM-based neural network with convolutional layers and dense layers.

Train the model on the dataset and validate it using a separate validation set.

Save the trained model and tokenizer for future predictions.

Provide a Gradio web interface for users to input news articles and get real-time predictions along with confidence visualization.
