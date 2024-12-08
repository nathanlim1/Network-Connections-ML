# README: Detection of Malicious Network Connections via Machine Learning

## Overview

This project aims to train a machine learning model to classify network connections as either attacks or normal connections, leveraging the KDD Cup 1999 dataset. The dataset provides comprehensive records of simulated network connections with labeled attack types, making it an excellent resource for evaluating intrusion detection systems.

The project uses a **Random Forest Classifier** to achieve high accuracy, recall, and precision in detecting network anomalies and malicious connections. The notebook also explores feature importance, hyperparameter tuning, and evaluates the model on both a 10% sample and the full dataset.

---

## Prerequisites

### Data Requirements
The necessary data files for this project are **not included in this repository** and must be manually downloaded and added to the `/data` directory. The following files are required:

- `kddcup.data_10_percent_corrected`: Used for initial training and evaluation.
- `kddcup.data.corrected`: Used for testing the model on the full dataset.

### Directory Structure
Ensure the following directory structure exists:

```
/data 
    ├── kddcup.data_10_percent_corrected 
    ├── kddcup.data.corrected
    
networkML.ipynb
```


---

## How to Run

1. **Prepare the Environment**:
   - Install required Python libraries such as `pandas`, `scikit-learn`, `matplotlib`, and `numpy`.
   - Ensure the `/data` directory contains the required files.

2. **Run the Notebook**:
   - Open `networkML.ipynb` in your Jupyter Notebook or Google Colab environment.
   - Execute the cells sequentially.

3. **Outputs**:
   - The notebook will produce a trained model, evaluate it on test data, and display performance metrics such as accuracy, precision, recall, and F1-score.
   - Feature importance visualizations and confusion matrices will be displayed to interpret the results.

---

## Results Summary

- **10% Sample Dataset**:
  - High performance in classifying attack vs. normal connections.
  - Insights into feature importance and model optimization.

- **Full Dataset**:
  - Accuracy: 99.99%
  - Precision: 99.99%
  - Recall: 99.99%
  - F1-Score: 99.99%

---

For any questions or issues, feel free to contact me!
