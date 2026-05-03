# Supply-Chain-Management-Data-Analysis

## Project Overview

This project analyzes supply chain data collected over a period of three years to understand the key factors affecting delivery delays and profitability. It combines exploratory data analysis (EDA) with a machine learning approach to predict whether a delivery will be delayed.

---

## Objectives

* Identify factors contributing to delivery delays
* Analyze the impact of delays on profitability
* Study the influence of region, time, and operational variables
* Build a predictive model for delay classification

---

## Dataset Description

The dataset contains three years of operational supply chain data, including:

* Order details
* Delivery status
* Delay duration
* Profit per order
* Regional information
* Time-based features (month, day, hour)

---

## Exploratory Data Analysis (EDA)

### Data Cleaning

* Removed canceled shipments
* Handled missing values
* Checked and removed duplicate records

---

### Delay Analysis

* Identified key factors contributing to delays
* Analyzed delay trends across:

  * Month
  * Day of the week
  * Hour of the day

---

### Profit Analysis

* Evaluated the impact of delays on profit
* Calculated percentage of delayed orders affecting losses
* Compared total profit and loss due to delays
* Analyzed profit variations across regions and operational conditions

---

## Key Insights

* Certain time periods have a higher probability of delays
* Delivery delays have a negative impact on profitability
* Regional differences influence both delays and profit outcomes
* Operational inefficiencies directly affect business performance

---

## Machine Learning Model

Random Forest Classifier
Binary classification:

* 1: Delayed
* 0: On-time

---

### Model Features

The model uses input features such as:

* Order-related details
* Time-based features
* Regional information
* Other operational factors

---

### Objective

Predict whether a delivery will be delayed based on input features

---

### Handling Imbalanced Data

Applied SMOTE (Synthetic Minority Oversampling Technique) to address class imbalance and improve model performance

---

## Tools and Technologies

* Python
* Pandas
* NumPy
* Matplotlib and Seaborn
* Scikit-learn
* Imbalanced-learn
* Jupyter Notebook

---

## Project Structure

```
├── data/
├── supply_chain_analysis.ipynb
├── README.md
```

---

## How to Run

1. Clone the repository

```
git clone https://github.com/your-username/repo-name.git
```

2. Install dependencies

```
pip install -r requirements.txt
```

3. Run the notebook

```
jupyter notebook
```

---

## Future Improvements

* Deploy the model as a web application
* Build an interactive dashboard for visualization
* Improve model performance using advanced algorithms
* Integrate real-time prediction capabilities

---

## Author

Prasoon Pallav

---

## Acknowledgement

This project demonstrates the application of data analysis and machine learning techniques to solve real-world supply chain problems.
