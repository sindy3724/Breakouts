# Breakouts
Repository for breakout sessions

Each breakout contains a copy of the case study, associated data files, and sample code (that may or may not be helpful).

<b>Week 8 Questions</b>

<b>Reading</b>

What is required for supervised learning?
Supervised learning requires a labeled dataset where each input example is associated with a correct output. The process involves:
Training Data: A large dataset with labeled examples.
Model: A function that maps inputs to outputs.
Loss Function: A measure of how well the model's predictions match the actual labels.
Optimization Algorithm: Typically gradient descent or stochastic gradient descent (SGD), which adjusts model parameters to minimize loss.
Evaluation Metrics: Metrics such as accuracy, precision, recall, and F1-score to assess performance on a test dataset

What is the advantage of backpropagation for neural networks?
Backpropagation allows efficient training of deep neural networks by computing gradients and updating weights to minimize error

What is the basic structure for CNNs?
A Convolutional Neural Network (CNN) processes images and structured data with multiple layers:
Convolutional Layers – Detect features like edges and patterns.
Activation Functions – Typically ReLU, which adds non-linearity to help the network learn better.
Pooling Layers – Reduce size while keeping important features.
Fully Connected Layers – Combine everything to make predictions.
Output Layer – Uses softmax (for classification) or another function to give final results

How do we compare performance of classification algorithms? 
The performance of classification algorithms is compared using various evaluation metrics, including:

Accuracy: The proportion of correctly classified samples.
Precision: The ratio of true positives to predicted positives.
Recall: The ratio of true positives to actual positives.
F1-Score: The harmonic mean of precision and recall.
ROC-AUC: Evaluates how well the classifier separates positive and negative classes.
Confusion Matrix: Provides a detailed breakdown of true positives, true negatives, false positives, and false negatives.
Training and Inference Time: Measures computational efficiency.
Overfitting vs. Generalization: Examined using performance on training vs. test data





