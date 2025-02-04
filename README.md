# Anomaly Detection using Deep Learning

## Overview
This project focuses on detecting anomalies using deep learning models. It explores various machine learning algorithms and deep learning techniques to identify anomalies in datasets effectively. Our approach achieves **higher accuracy** compared to existing IoT anomaly detection methods.

## Dataset Preprocessing
- **Oversampling**: Applied to balance the dataset.
- **Feature Engineering**: Processed features like `Source_id`, `Operation`, and `DestinationServiceAddress`.

## Model Training
The following optimizers and epochs were used during training:

| Optimizer | Epochs | Training Accuracy | Testing Accuracy | Training Loss | Testing Loss |
|-----------|--------|------------------|------------------|--------------|--------------|
| Adam      | 10     | 98.53%           | 99.87%           | 0.0523       | 0.0070       |
| Adam      | 15     | 98.35%           | 99.74%           | 0.0594       | 0.0093       |
| RMSprop   | 10     | 98.23%           | 99.80%           | 0.0771       | 0.0103       |
| RMSprop   | 15     | 98.43%           | 99.77%           | 0.0846       | 0.0136       |

## Comparison with State-of-the-Art Research
Our results show **higher accuracy** compared to existing IoT anomaly detection techniques.

- The paper *"All Eyes on You: Distributed Multi-Dimensional IoT Microservice Anomaly Detection"* reports a **99% accuracy** with a **false positive rate of 0.2%** and a **detection rate of 96.3%**.
- **Our Multilayer Perceptron (MLP) model achieves 99.87% accuracy**, which is superior to their results.
- **Our Decision Tree model achieves 99.96% accuracy**, demonstrating state-of-the-art performance in anomaly detection.

### Machine Learning Algorithms & Accuracy
| Algorithm | Accuracy |
|-----------|----------|
| **Decision Tree** | **99.96%** |
| **Multilayer Perceptron (MLP)** | **99.87%** |
| Random Forest | 98.97% |
| SVM | 85.42% |
| KNN | 88.05% |
| Logistic Regression | 81.91% |


