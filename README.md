# Title_gen
This project implements a machine-learning pipeline to generate text using LSTM neural networks. It processes datasets containing YouTube video metadata and applies natural language processing techniques to create relevant text based on user-provided input. The project focuses on titles from the "Entertainment" category to train the model.

Key Features:
Dataset Integration:

Combines multiple datasets of YouTube video metadata (e.g., US, CA, GB).
Extracts category titles from JSON files to map each video's category.
Data Preprocessing:

Filters video titles from the "Entertainment" category.
Cleans text by removing punctuation and converting it to lowercase.
Sequence Generation:

Tokenizes text into sequences of words.
Generates input-output pairs for training based on n-gram sequences.
LSTM Model Architecture:Embedding layer for word representation.
LSTM layer for sequence processing.
Dense output layer with softmax activation for word prediction.
Interactive Text Generation:

Accepts user input (seed text and word count).
Generates contextually relevant text based on the trained model.
User-Defined Inputs:

Users can specify dataset paths, seed text, and the number of words for text generation.


Applications:
Automated title generation for video content.
Text augmentation for creative writing.
Enhancing user engagement with AI-generated suggestions.
Output Example:
The trained model generates a sequence of words based on input seed text, such as:

Input: happy
Output: "Happy moments and laughter with friends"
This project demonstrates the practical use of deep learning models in text generation, providing a foundation for further exploration in natural language processing.
