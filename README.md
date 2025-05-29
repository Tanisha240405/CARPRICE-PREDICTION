# CARPRICE-PREDICTION# Car Price Prediction

This project is a machine learning model to predict car prices (MSRP) using various features such as make, year, engine specifications, and more. The dataset used is provided in `CarPrice_Assignment.csv`.

## Project Structure

- **Car_Price_Prediction_New.ipynb**: Jupyter notebook containing all steps from data preprocessing to model evaluation.
- **CarPrice_Assignment.csv**: Dataset used for training and testing the model.

## Steps Covered

1. **Data Loading**: Load and inspect the dataset using pandas.
2. **Data Cleaning**: Handle missing values and remove irrelevant columns.
3. **Feature Engineering**: One-hot encode categorical variables and normalize features if necessary.
4. **Model Building**: Use Linear Regression to build a predictive model.
5. **Model Evaluation**: Evaluate using Mean Squared Error and R² score.
6. **Sample Prediction**: Make and compare predictions with actual car prices.

## Requirements

- Python 3.7+
- Libraries:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn

You can install the dependencies using:

\`\`\`bash
pip install pandas numpy matplotlib seaborn scikit-learn
\`\`\`

## How to Use

Open the Car_Price_Prediction_New.ipynb notebook in Jupyter.

Run all cells to train and evaluate the model.

Optionally, try modifying the dataset or model to improve accuracy.

## License

This project is for educational purposes only.
