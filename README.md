# Linear Regression: Noise, Outliers and Overfitting

## About the Project

This project is part of my work in mathematics and data analysis. I wanted to understand how linear regression works and what happens when the data changes or the model becomes more complex.

I used Python to calculate regression lines, make predictions, visualize the results and measure prediction errors.

## What I Worked On

- Calculating a linear regression slope and intercept using the least-squares method.
- Making predictions and calculating residuals.
- Using MAE, MSE and RMSE to measure model errors.
- Adding random noise to a dataset and comparing the results.
- Testing how an outlier affects a regression line.
- Comparing polynomial models with different degrees.

## Tools Used

- Python
- NumPy
- pandas
- Matplotlib
- Jupyter Notebook

## Experiments

### 1. Linear Regression

I started with a small dataset and calculated the regression equation manually using the least-squares formulas. I then used the equation to make predictions and plotted the regression line alongside the original data.

### 2. Adding Noise

I added random noise to the original values using two different noise levels. I compared the datasets and their regression lines to see how the added variation affected the results.

### 3. Outliers

I changed one value in a copy of the original dataset to create an outlier. I then fitted another regression line and compared it with the original model.

### 4. Polynomial Models

I fitted polynomial models of degrees 1, 2 and 4 to the same dataset. The higher-degree model followed the observed points more closely, which helped me understand why a more complex model is not always the best choice.

## What I Learned

This project helped me understand the relationship between the data, the regression equation and the resulting predictions.

I saw how noise can change a fitted line, how an outlier can influence regression, and how a more complex model can fit a small dataset very closely.

I also learned that a model's error on the data it was fitted on does not tell us how well it will predict new observations.

## Limitations

The dataset contains only five observations, so the experiments are mainly useful for learning and illustrating the concepts. More data and a separate test dataset would be needed to evaluate how well the models generalize to unseen observations.

## How to Run

Install the required libraries:

```bash
pip install numpy pandas matplotlib jupyter
```

Open `notebooks/linear_regression_analysis.ipynb` in Jupyter Notebook or VS Code and run the cells in order.

## Project Structure

```text
math-final-project/
├── README.md
└── notebooks/
    └── linear_regression_analysis.ipynb
```