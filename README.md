# MSCS_634_Lab_4

# MSCS 634 – Lab 4: Regression Analysis with Regularization
🧪 Lab Overview
In this lab, I experimented with various regression techniques using the Diabetes dataset from sklearn.datasets. The primary aim was to create models that predict the progression of the disease based on medical features and to assess how regularization can help mitigate overfitting and enhance model performance.

📂 Files Included
Lab4_Regression_and_Regularization.ipynb
This Jupyter Notebook contains the complete code, model implementations, visualizations, and evaluation metrics.

README.md
This document provides insights into the lab’s purpose, process, challenges, and results.

🔍 Objectives
My objectives for this lab were to:

Implement and compare the following techniques:

Simple Linear Regression

Multiple Linear Regression

Polynomial Regression

Ridge Regression

Lasso Regression

Evaluate the models using metrics such as:

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

Root Mean Squared Error (RMSE)

R-squared (R²)

Visualize the predictions and residuals for deeper insights.

Investigate how regularization techniques help control model complexity and prevent overfitting.

📊 Key Insights
Multiple Regression outperformed Simple Linear Regression by incorporating all available features.

Polynomial Regression showed better accuracy for lower degrees but tended to overfit as the degree increased.

Both Ridge and Lasso Regression assisted in managing overfitting. Ridge effectively reduced model variance, while Lasso performed feature selection by shrinking some coefficients to zero.

Regularization was crucial for improving the model's ability to generalize.

⚠️ Challenges Faced
Choosing the right polynomial degree without overfitting was challenging.

Experimenting with different alpha values for Ridge and Lasso required careful trial and error.

Visualizing performance for high-dimensional regressions was difficult, so I relied heavily on residual plots and evaluation metrics.

🛠️ Technologies Used
Python 3

Jupyter Notebook

Libraries: scikit-learn, pandas, numpy, matplotlib, seaborn

✅ How to Run
Clone or download this repository.

Open the file Lab4_Regression_and_Regularization.ipynb in Jupyter Notebook, JupyterLab, or Google Colab.

Run the cells in sequence to replicate my results and visualizations.

