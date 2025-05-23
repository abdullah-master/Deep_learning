# Deep Learning Project

## Overview
This repository contains deep learning projects focused on solving real-world problems using Artificial Neural Networks (ANNs). The projects are implemented using Python and TensorFlow/Keras, with additional support from libraries like Pandas, NumPy, and Scikit-learn.

### Current Projects

#### 1. Heart Disease Prediction
- **Objective**: Predict whether a patient is at risk of heart disease based on their medical records.
- **Dataset**: Contains features like age, cholesterol, and blood pressure, along with a target column indicating the presence of heart disease.
- **Model**: A Feedforward ANN with two hidden layers and a Sigmoid output layer for binary classification.
- **Key Steps**:
  - Data preprocessing (handling missing values, feature scaling, etc.)
  - Addressing class imbalance using class weights
  - Model training with early stopping
  - Evaluation using metrics like accuracy, precision, and recall

#### 2. MNIST Dataset Classification (Upcoming)
- **Objective**: Classify handwritten digits from the MNIST dataset.
- **Model**: Convolutional Neural Network (CNN).

## Repository Structure
```
Deep_learning/
│
├── Heart Disease/
│   ├── case study.pdf
│   ├── heart.csv
│   ├── scenario_2.ipynb
│
├── MNIST Dataset/
│   ├── Case study.pdf
│   ├── scenario1.ipynb
│
└── README.md
```

## Requirements
- Python 3.8+
- TensorFlow 2.0+
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/abdullah-master/Deep_learning.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Deep_learning
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Open the Jupyter Notebook for the desired project and run the cells.

## Contributing
Contributions are welcome! Feel free to open issues or submit pull requests to improve the repository.

## License
This project is licensed under the MIT License.
