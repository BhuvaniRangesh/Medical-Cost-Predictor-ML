# Medical-Cost-Predictor-ML
Medical Cost Predictor (Linear Regression)

This project implements Linear Regression from scratch to predict annual medical insurance charges. The implementation follows the methodology taught in the DeepLearning.AI Machine Learning Specialization by Andrew Ng.
🎯 Project Objective

The goal is to predict the charges (medical insurance cost) for an individual based on three key features:

    Age: The age of the primary beneficiary.

    BMI: Body Mass Index, providing an understanding of body weight relative to height.

    Smoker: Whether the person is a smoker (1) or a non-smoker (0).

🛠️ Technical Concepts Implemented

I chose to implement the math manually using NumPy to ensure a deep understanding of how the algorithm learns.
1. Feature Scaling (Z-score Normalization)

Since features like age and bmi have different ranges, I implemented normalization to help Gradient Descent converge faster.
2. Cost Function

Used the Mean Squared Error (MSE) to measure how well our model is performing:
J(w,b)=2m1​i=0∑m−1​(fw,b​(x(i))−y(i))2
3. Gradient Descent

Implemented the gradient descent algorithm to update parameters w and b simultaneously until the cost reaches a global minimum.
📊 Results

The model successfully reduces the cost over time. After 1,000 iterations with a learning rate of α=0.1, the learning curve shows a smooth convergence.
🚀 How to Run

    Clone this repository.

    Ensure you have numpy, pandas, and matplotlib installed.

    Run the Jupyter Notebook or Python script to see the predictions.
