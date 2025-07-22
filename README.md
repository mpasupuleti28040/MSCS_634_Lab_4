# MSCS_634_Lab_4
# MSCS 634 – Lab 4: Regression Analysis with Regularization
🧪 Lab Overview
In this lab, I explored several regression techniques using the Diabetes dataset from sklearn.datasets. The main goal was to develop models that predict disease progression based on various medical features and evaluate how regularization techniques can help reduce overfitting and improve model performance.

📂 Files Included
Lab4_Regression_and_Regularization.ipynb
This Jupyter Notebook contains all the code, model implementations, visualizations, and evaluation metrics.

README.md
You're reading it! This file provides an overview of the lab’s objectives, insights, challenges, and results.

🔍 Objectives
The key objectives for this lab were to:

Implement and compare various regression techniques, including:

Simple Linear Regression

Multiple Linear Regression

Polynomial Regression (Degree 2)

Ridge Regression

Lasso Regression

Evaluate the models using the following metrics:

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

Root Mean Squared Error (RMSE)

R-squared (R²)

Visualize predictions and residuals to gain deeper insights.

Understand how regularization can help control model complexity and prevent overfitting.

📊 Key Insights
Multiple Regression performed better than Simple Linear Regression by utilizing all available features.

Polynomial Regression (degree 2) showed improved accuracy but had potential overfitting concerns, which were briefly discussed in the README.

Ridge and Lasso Regression were both effective in addressing overfitting. Ridge helped reduce model variance, while Lasso performed feature selection by shrinking some coefficients to zero.

Regularization played a critical role in improving the model’s generalization capabilities.

⚠️ Challenges Faced
Determining the optimal degree for Polynomial Regression without overfitting was challenging.

Experimenting with different alpha values for Ridge and Lasso required careful tuning and comparisons.

Visualizing the performance of high-dimensional regressions was not straightforward. I relied on residual plots and performance metrics for better understanding.

🛠️ Technologies Used
Python 3

Jupyter Notebook

Libraries: scikit-learn, pandas, numpy, matplotlib, seaborn

✅ How to Run
Clone or download this repository.

Open the file Lab4_Regression_and_Regularization.ipynb in Jupyter Notebook, JupyterLab, or Google Colab.

Run the cells sequentially to reproduce the results and visualizations.

📌 About Me
I am currently enrolled in MSCS 634 – Data Analytics at the University of the Cumberlands.
This lab was an essential part of my coursework, allowing me to gain valuable insights into how different regression models perform, how regularization helps in reducing overfitting, and how visualization tools like residual plots enhance model evaluation.

