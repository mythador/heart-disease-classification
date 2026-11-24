# Heart Disease Classification Workflow

## Overview

This project was completed for my Week 4 Machine Learning assignment at Mid-State Technical College.

The goal was to build and compare two classification models using the Cleveland Heart Disease dataset. The focus was on preparing data correctly, preventing data leakage, evaluating model performance, and understanding classification errors.

## Dataset

The project uses the Cleveland Heart Disease dataset, which contains 303 records and 11 columns, including the target variable.

## Models Used

- **DummyClassifier:** Establishes a baseline by predicting the most common class.
- **Logistic Regression:** Uses a classification model to predict the target.
- **Random Forest:** Uses 200 decision trees to make predictions.

## Tools and Libraries

- Python
- Jupyter Notebook
- pandas
- NumPy
- Matplotlib
- scikit-learn

## Results

Both models performed better than the baseline.

Logistic Regression achieved approximately 88.52% accuracy, while Random Forest achieved approximately 85.25%.

Logistic Regression also had better recall and fewer false negatives, making it the preferred model for this assignment.

## Running the Project

1. Download or clone the repository.
2. Install the required Python libraries.
3. Open `HeartDisease.ipynb` in VS Code or Jupyter Notebook.
4. Make sure `Cleveland-303-10.csv` is in the same folder.
5. Run the notebook cells from top to bottom.

## Conclusion

This project helped me understand how to prepare datasets, train classification models, compare their performance, and recognize possible overfitting. It also demonstrated why evaluating different types of prediction errors is important instead of relying only on accuracy.

This project is for educational purposes and is not intended for medical diagnosis or clinical decision-making.