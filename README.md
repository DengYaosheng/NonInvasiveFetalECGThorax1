## Non-Invasive Fetal ECG Thorax1 Dataset Analysis

## Introduction

This repository contains code for analyzing the Non-Invasive Fetal ECG Thorax1 dataset. The dataset comprises time-series data of fetal electrocardiograms (ECG) along with associated labels. The aim is to explore the dataset, perform feature extraction, dimensionality reduction, model training, and evaluation to classify different types of fetal ECG signals or identify specific events within the ECG data.

## Contents

- `data_train.xls`: Training dataset file containing fetal ECG time-series data and labels.
- `data_test.xls`: Test dataset file containing fetal ECG time-series data and labels.
- `fetal_ecg_analysis.py`: Python script for data processing, model training, and evaluation.
- `README.md`: This README file providing an overview of the project.

## Usage

1. **Data Preparation**: Ensure the `data_train.xls` and `data_test.xls` files are available.
2. **Data Processing**: Run the `fetal_ecg_analysis.py` script to process the data, visualize the training dataset, train the model, and evaluate its performance.
3. **Model Evaluation**: Check the classification accuracy, F1 scores, and classification report generated by the script to assess the model's performance.

## Requirements

- Python 3.x
- Required Python libraries: NumPy, pandas, matplotlib, seaborn, scikit-learn

- ## Result

- Label 42 test result:

![lable_42](https://github.com/DengYaosheng/NonInvasiveFetalECGThorax1/assets/41530023/94258279-689a-4e6a-ae6b-b8f36539420b)


## References

- [Link to the Non-Invasive Fetal ECG Thorax1 dataset](https://example.com/dataset)
- [Documentation for scikit-learn](https://scikit-learn.org/stable/documentation.html)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


