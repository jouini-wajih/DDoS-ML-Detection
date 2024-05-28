# Detection of DDoS Attacks Using Machine Learning

## Introduction

In today's digital landscape, Distributed Denial of Service (DDoS) attacks pose a significant threat to organizations and individuals, potentially causing major disruptions in online services and resulting in financial and reputational losses. This project aims to develop a machine learning-based system to detect and classify DDoS attacks in network traffic.

## Summary

DDoS attacks overwhelm a target system with an excessive volume of requests, rendering it temporarily unavailable to legitimate users. Unlike traditional DoS attacks, DDoS attacks utilize a network of compromised devices to amplify their impact, making them harder to counter.

Our project, "Detection of DDoS Attacks Using Machine Learning Algorithms," aims to develop an advanced system to detect and classify DDoS attacks in network traffic using machine learning algorithms such as Logistic Regression, Support Vector Machines (SVM), Random Forest, and Gradient Boosting. We evaluate their performance on datasets of network traffic features.

## Objectives

1. **Data Collection and Preprocessing**: Acquire a comprehensive dataset containing examples of normal network traffic and various types of DDoS attacks. Preprocess and clean the data to ensure consistency and reliability for analysis.
2. **Algorithm Selection and Implementation**: Explore and choose machine learning algorithms suitable for binary classification tasks. For this project, we implement Logistic Regression, SVM, Random Forest, and Gradient Boosting.
3. **Model Training and Evaluation**: Train predictive models using the selected algorithms and the preprocessed data. Evaluate the models' performance using metrics such as accuracy, recall, and F1 score.
4. **Comparative Analysis**: Conduct a thorough comparative analysis of the algorithms' effectiveness in detecting DDoS attacks. Understand the trade-offs between different algorithms in terms of accuracy, efficiency, and adaptability.
5. **Reducing False Positives**: Design algorithms to minimize false positive rates by distinguishing between legitimate traffic fluctuations and actual DDoS attacks. Achieving higher accuracy will reduce unnecessary resource load caused by false alarms.

## Project Structure

- `data/`: The dataset used for training and evaluation.
- `notebooks/`: Jupyter notebooks for exploratory data analysis and model development.
- `README.md`: This file, providing an overview of the project.

## Getting Started

### Prerequisites

- Python 3.x
- Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/jouini-wajih/DDoS-ML-Detection.git
   cd ddos-detection-ml
