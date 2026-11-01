# Assignment 1: Data Profiling (EDA)

**Course:** Data Engineering  
**Group:** 36

## Group Members

1. Emmy Natasha binti Rosmani (A211993)
2. Nur Najwa Balqis binti Sulaiman (A212324)
3. Hannah binti Mohd Rose Rizal (A212377)
4. Wan Imran Asyraf Bin Wan Abdul Manan (A212326)

## Project Overview

This assignment focuses on identifying and handling data quality issues using the Messy Employee Dataset. The analysis includes missing values, outliers, duplicate records, inconsistent formats, invalid values, and potential privacy and bias risks.

## Dataset Information

**Dataset:** Messy Employee Dataset  
**Source:** [Kaggle – Messy Employee Dataset](https://www.kaggle.com/datasets/desolution01/messy-employee-dataset)

The dataset contains 1,020 employee records and 12 original columns. It is a synthetic dataset containing intentionally introduced data quality problems.

## Tools and Libraries

- Google Colab / Jupyter Notebook
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

## How to Run the Notebook

1. Download the dataset from the Kaggle link provided above.
2. Open `Assignment_1_Data_Profiling_(EDA).ipynb` in Google Colab.
3. Upload `Messy_Employee_dataset.csv` to the Google Colab Files panel.
4. Click **Runtime → Run all** to execute all cells.
5. The notebook will display the data profiling results, cleaning processes, and diagnostic visualizations.

**Note:** The CSV file may need to be uploaded again when starting a new Google Colab session.

## Assignment Contents

The notebook covers the following sections:

1. Scenario and Data Source
2. Initial Data Profiling
3. Missing Value Detection and Handling
4. Outlier Detection and Analysis
5. Other Data Quality Issues
6. Exploratory Diagnostic Charts
7. PII and Bias Risk Assessment
8. Conclusion and Dataset Limitations

## Conclusion

The data profiling process identified several data quality issues, particularly missing values, invalid phone numbers, and repeated identifiers. Appropriate cleaning and validation methods were applied while preserving important information. Some limitations remain, and further validation would be required before using the dataset for real-world HR decisions.
