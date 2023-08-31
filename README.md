# CODSOFT-ML-TASK-2

# Credit Card Fraud Detection
Credit card fraud detection is the process of identifying and preventing fraudulent transactions made using credit cards . It involves the use of various policies, tools, methodologies, and practices to detect and mitigate instances of fraud.


## Overview
This project aims to develop a machine learning model for detecting credit card fraud. The goal is to accurately identify fraudulent transactions and minimize the impact on customers and businesses.

## Installation
1. Clone the repository: `git clone https://github.com/Sarbani3pal/CODSOFT-ML-TASK-2.git`
2. Install the required dependencies

## Data
The dataset used for training and testing the model is obtained from creditcard.csv . It contains transaction records with labeled fraud cases. The data is provided in CSV format and has been preprocessed to handle missing values and normalize numerical features.

## Model
For this project, I have employed a Random Forest Classifier as our machine learning model. The RandomForest algorithm is known for its ability to handle imbalanced datasets and capture complex relationships between features.

I have used the following hyperparameters for the Random Forest Classifier:
- Number of estimators: 100
- Maximum depth: 10

Feature engineering techniques, such as PCA and feature scaling, were applied to the dataset to improve model performance.

## Usage
To run the credit card fraud detection model:
1. Ensure you have the required dependencies installed (see Installation section).
2. Run the `app.py` script:
This script will load the pre-trained model, perform predictions on new data, and generate a fraud detection report.

## Results
This trained model achieved an accuracy of 99.5% and a precision of 97% on the test dataset. The confusion matrix and ROC curve are shown below:

ROC Curve ![roc curve](https://github.com/Sarbani3pal/CODSOFT-ML-TASK-2/assets/106859451/1b7fb93e-38cf-49d7-9e1f-b26867cea8ae) Confusion Matrix [cm](https://github.com/Sarbani3pal/CODSOFT-ML-TASK-2/assets/106859451/e8798a5e-21dd-4a07-a187-c10f093e60ff)




For a detailed analysis of the model's performance, please refer to the https://github.com/Sarbani3pal/CODSOFT-ML-TASK-2/new/main?readme=1 file.

## Demo Video
Check out the demo video below to see the credit card fraud detection model in action:

[![Demo Video](https://www.linkedin.com/posts/sarbani-pal-219454211_crefitcardfrauddetection-codsoft-innovation-activity-7102865506524643329-7TxL?utm_source=share&utm_medium=member_desktop)

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgements
- Kaggle for providing the dataset
- Scikit-learn library for the machine learning algorithms
- Pandas and NumPy libraries for data handling and preprocessing

## Contact
For any questions or further information, please contact sarbaniflakes@gmail.com
