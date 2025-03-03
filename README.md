**Objective:**

The objective of this code is to implement a simplified version of the Word2Vec model using a neural network to learn **word embeddings** from a given text dataset. Specifically, the code focuses on:

1. **Text Preprocessing**: Cleaning and preparing text by removing punctuation, digits, and stop words, and converting the text to lowercase to ensure uniformity and quality of input data.

2. **Context Window Generation**: Using a sliding window approach, the code generates word pairs consisting of a target word and its surrounding context words, which are essential for training a Word2Vec-like model.

3. **One-Hot Encoding**: The generated word pairs are encoded using one-hot encoding, creating input (X) and output (Y) matrices where the input corresponds to a target word, and the output corresponds to its context word.

4. **Neural Network Model**: A simple neural network is built and trained to predict context words from target words. The network learns low-dimensional embeddings (2D in this case) that represent the semantic meaning of words based on their context in the training data.

5. **Visualization of Word Embeddings**: The learned word embeddings are visualized in a 2D plot, where semantically similar words are expected to cluster together, showing how the model has learned to represent word relationships in a continuous space.

This approach demonstrates how neural networks can be used to learn distributed representations of words, which is a foundational concept in modern natural language processing tasks.
