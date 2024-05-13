# PCSE24-08
# Credit Card Fraud Detection Project

## Overview
This project aims to conduct a comprehensive comparison between two distinct algorithms for anomaly detection: Isolation Forest (IF) and Local Outlier Factor (LOF). Anomaly detection is crucial in identifying unusual or unexpected occurrences within datasets, particularly in the domain of credit card fraud detection.

### Algorithms
#### Isolation Forest (IF)
IF is an unsupervised methodology specifically designed for outlier detection. It employs the concept of "isolation" to segregate individual data instances from the rest of the dataset, departing from conventional methods reliant on distance and density metrics. IF offers improved accuracy and efficiency in anomaly identification, with minimal resource allocation demands.

#### Local Outlier Factor (LOF)
LOF algorithm assesses outliers based on a data point's local variances compared to its neighbors, gauging outliers based on local density. By emphasizing local relationships and densities, LOF unveils nuanced anomalies often overlooked by traditional methods, enriching the granularity of anomaly detection within datasets.

### Implementation
The project utilizes three distinct subsets of the dataset: training set, validation set, and testing set. The model undergoes training on the training dataset, followed by hyperparameter tuning on the validation set, and final evaluation on the testing data. Notably, the test dataset is strictly prohibited from use during classifier training.

### Evaluation Metrics
Evaluation of the models' efficacy involves assessing metrics such as accuracy rate, precision, recall, and F1-score. Additionally, confusion matrix metrics including true positives, true negatives, false positives, and false negatives are utilized to evaluate model performance.

## Data
The project utilizes two sets of data: European and German credit card fraud transaction datasets. Evaluation initially involves assessing models without adjusting class distribution, followed by the application of resampling techniques such as random undersampling, AllKNN, SMOTE, and SMOTE-ENN. Evaluation metrics are recorded and analyzed after each resampling technique application to understand their impact on model accuracy.

## Proposed Model
The proposed model configuration is illustrated in the block diagram (Fig. 1), outlining key steps including data collection, processing, identification of suitable models, subsequent training and testing, and comprehensive evaluation. This stage is pivotal in driving the refinement of machine learning model accuracy.

## Conclusion
The project aims to enhance credit card fraud detection through a comparative analysis of IF and LOF algorithms, alongside the evaluation of resampling techniques' impact on model accuracy. By leveraging advanced anomaly detection methodologies and evaluation techniques, the project endeavors to contribute to the development of robust fraud detection systems.
