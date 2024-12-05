# Salary-Prediction# Linear Regression on Salary Data

This project demonstrates a linear regression analysis on a dataset containing years of experience and corresponding salaries. It uses Python and popular libraries like NumPy, Pandas, and scikit-learn for data analysis and model building.

---

## Dataset Overview

The dataset includes two columns:
- **YearsExperience**: The number of years an individual has worked.
- **Salary**: The corresponding annual salary.

### Dataset Statistics:
- Total records: 35
- **Years of Experience**: Range from 1.1 to 13.5 years
- **Salary**: Range from $37,731 to $139,465

---

## Libraries Used
- **Pandas**: For data manipulation and analysis
- **NumPy**: For numerical computations
- **Matplotlib**: For data visualization
- **scikit-learn**: For machine learning model building and evaluation

---

## Steps Performed

1. **Data Exploration**:
   - Previewed the dataset using `head()`.
   - Generated statistical summaries using `describe()`.

2. **Data Visualization**:
   - Created histograms for individual variables.
   - Generated scatter plots to analyze the relationship between years of experience and salary.

3. **Data Splitting**:
   - Split the data into training (70%) and testing (30%) sets using a random mask.

4. **Linear Regression Model**:
   - Built a linear regression model using scikit-learn.
   - Calculated coefficients and intercept:
     - **Coefficients**: 8867.87
     - **Intercept**: 28223.36

5. **Model Evaluation**:
   - Predicted salaries on the test data.
   - Plotted the regression line and test points.
   - Evaluated the model using:
     - **Mean Absolute Error**: 5540.04
     - **Residual Sum of Squares (MSE)**: 41338191.69
     - **R² Score**: 0.94

---

## Visualizations

### Data Distribution
- Histogram of Years of Experience and Salary.

### Relationship Plot
- Scatter plot of Years of Experience vs Salary with a regression line overlaid.

---

## Key Findings

- Strong positive correlation between years of experience and salary.
- Model achieves high accuracy with an R² score of 0.94, indicating good predictive performance.

---

## Usage

1. **Install Dependencies**:
   Ensure the following Python libraries are installed:
   ```bash
   pip install numpy pandas matplotlib scikit-learn
