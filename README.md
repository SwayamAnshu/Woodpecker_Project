# Woodpecker_Project
Given repository is solely made to develop the Fraud Detection System under Woodpecker Hackathon contest.


# Fraud Detection Models(Prototype)
This repository contains implementations of two distinct fraud detection models:

1.  Traditional Model: A conventional machine learning approach for detecting fraud. This model uses established algorithms and techniques to classify and identify fraudulent activities based on historical data.

2.  GAN Model: A Generative Adversarial Network (GAN) based approach. This model leverages advanced neural network techniques to generate synthetic examples of fraud and improve detection performance through adversarial learning.

# Future Work

In future updates, these two models will be integrated into a unified framework. The combined approach aims to leverage the strengths of both the traditional and GAN models to enhance the overall accuracy and robustness of the fraud detection system. 

# Problem:

1) Fraud detection is a truly important problem to any e-commerce store, and companies put a lot of money to prevention because a single fraud can cost them a lot of money as well.

2) One of the biggest issues with this problem is that the vast majority of users will not be fraudulent. It is estimated that only 0.1% of online transactions are fraudulent, but given the volume of transactions that occur every day, that means a lot of money.

This will make it harder for us to detect the underlying patterns with the information available. This will cause our dataset to be highly imbalanced, so we need to use different sample techniques and use different metrics.

Thus, we are going to see how we can help solve this problem using Deep Learning algorithms using tools such as Python, TensorFlow and Keras.

# OUR OBJECTIVE: 

To build a fraud detection classifier that, given a new transaction, can tell us if it is fraudulent or not with a correspondent confidence level. # Which are our classes? : 

“0” label = Classifier is NOT fraudulent
“1” label (classifier IS fraudulent)

We are going to build both a deep learning network to try to do so, and apply more traditional ML algorithms such as Random Forest as well as GAN based generative AI model. 

Machine Learning and Deep Learning techniques complement each other; in our case, we will be doing A|B testing to see which mode performs best, so once we cover our deep neural network, we are going to start using machine learning using the Python sckit-learn library.

# Contributing
Feel free to open issues or submit pull requests if you have suggestions or improvements. Your contributions are welcome!

# License
This project is licensed under the MIT License.
