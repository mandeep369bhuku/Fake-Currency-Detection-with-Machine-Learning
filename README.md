# Fake-Currency-Detection-with-Machine-Learning
Using logistic regression to identify fake currency
Fake Currency Detection is a real problem for both individuals and businesses. Counterfeiters are constantly finding new methods and techniques to produce counterfeit banknotes, which are essentially indistinguishable from real money. At least for the human eye. In this article, I will introduce you to Fake Currency Detection with Machine Learning.

Fake Currency Detection is a task of binary classification in machine learning. If we have enough data on real and fake banknotes, we can use that data to train a model that can classify the new banknotes as real or fake.

The dataset I will use in this task for fake currency detection can be downloaded from dataset file. The dataset contains these four input characteristics:

- The variance of the image transformed into wavelets
- The asymmetry of the image transformed into wavelets
- Kurtosis of the image transformed into wavelets
- Image entropy
