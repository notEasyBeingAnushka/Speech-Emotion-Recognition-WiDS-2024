# Week 2
Hello everyone! Welcome to week 2, where you'll dive into the core of machine learning, exploring two fundamental topics: regression and classification. These techniques will serve as the foundation for building predictive models and understanding how machines can learn from data to make informed decisions. Let's get started!
# Resources
## What is the difference between regression and classification?
Regression and classification are two key machine learning tasks. Regression predicts continuous numerical values, such as prices or temperatures, while classification assigns data into discrete categories, like spam detection or image classification. While regression focuses on numerical predictions, classification is used for categorical decision-making.
For a deeper understanding of these differences, here's a helpful article: [Difference explanation](https://www.javatpoint.com/regression-vs-classification-in-machine-learning)
<br>

Now that we've covered the basic difference between regression and classification, let's move on to explore the different types within each of these tasks.

## Regression 
Regression is a type of machine learning task that involves predicting a continuous numerical value based on input data. It is used when the output variable is a real number, such as predicting house prices, stock market trends, or temperature forecasts. The goal of regression is to find the relationship between the dependent variable (the output) and one or more independent variables (the inputs) to make accurate predictions. 

We will explore three types of regression - 
- ### Linear Regression
    - [Video Tutorial](https://youtu.be/7ArmBVF2dCs?si=A9VVZMGBa51alAIJ)
    - [Article](https://www.geeksforgeeks.org/linear-regression-implementation-from-scratch-using-python/)
- ### Ridge Regression
    - [Video Tutorial](https://youtu.be/Q81RR3yKn30?si=PSsC-qxrluSk_eLp)
    - [Article](https://www.geeksforgeeks.org/implementation-of-ridge-regression-from-scratch-using-python/)
- ### Logistic Regression
    - [Video Tutorial](https://youtu.be/yIYKR4sgzI8?si=h-myOtJxpLLIoXB-)
    - [Article](https://www.geeksforgeeks.org/implementation-of-logistic-regression-from-scratch-using-python/)
  
Although logistic regression is used for classification tasks, it’s still categorized as regression because it predicts probabilities (continuous values) for different classes. [An Interesting Article](https://ashish-mehta.medium.com/why-is-logistic-regression-called-regression-if-it-is-a-classification-algorithm-9c2a166e7b74) explains this further.

For each of the above types, the videos will offer a deeper understanding of the concepts and intuition, while the articles will guide you through the implementation of these techniques in Python.

## Classification
Classification is a machine learning task where the goal is to assign input data to predefined categories or labels. Unlike regression, which predicts continuous values, classification deals with discrete outcomes, such as labeling emails as "spam" or "not spam," or identifying objects in images. The model learns from labeled data to make predictions on new, unseen data.

We are going to look at two classification models:
- ### Naive Bayes Classifier
    - [Video Tutorial](https://youtu.be/O2L2Uv9pdDA?si=gIi_vdJOZmGimaJ-)
    - [Article](https://www.geeksforgeeks.org/naive-bayes-classifiers/)
- ### Support Vector Machines (SVM)
    - [Video Tutorial](https://youtu.be/ny1iZ5A8ilA?si=3wjFV4-fxQjY5mVT)
    - [Article](https://www.geeksforgeeks.org/support-vector-machine-algorithm/)
    - [Another article](https://medium.com/@gallettilance/support-vector-machines-16241417ee6d)

Similar to the regression models, the videos will provide a clear understanding of the intuition and concepts behind each classification model, while the articles will walk you through the Python implementation of these techniques.

# Assignments
This week contains 2 assignments -
- ## Logistic Regression
  In this assignment, you will implement logistic regression from scratch using the breast cancer dataset from scikit-learn. You will begin by preparing the data, scaling it, and splitting it into training and testing sets. Next, you'll implement the logistic regression algorithm, including the sigmoid function and binary cross-entropy loss, and evaluate the model's performance through accuracy and loss metrics.
- ## Support Vector Machines (SVM)
  In this assignment, you will implement a Support Vector Machine (SVM) from scratch. You'll begin by understanding key concepts like hyperplanes, margins, and the optimization problem that SVMs aim to solve. Then, you'll implement the SVM algorithm, including the gradient descent process for updating weights and bias. Finally, you'll apply this to a dataset, complete the necessary functions, and evaluate the model's performance using accuracy.
