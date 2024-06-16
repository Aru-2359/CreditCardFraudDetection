# Credit Card Fraud Detection 🕵🏼‍♀️🕵🏼‍♀️

This project aims to detect credit card fraud using machine learning techniques, specifically undersampling and three different classifiers: logistic regression, random forest, and decision tree.

## Dataset

The dataset used in this project contains transaction data from credit cards, including features V1 to V28 (anonymized for confidentiality), transaction time (Time), transaction amount (Amount), and a binary target variable (Class) indicating fraud (1) or not (0).

## Techniques Used

### Undersampling

To address the class imbalance in the dataset, undersampling of the majority class (non-fraudulent transactions) was performed. This involved randomly selecting samples from the majority class to match the number of samples in the minority class (fraudulent transactions).

### Classifiers Implemented

1. **Logistic Regression:**
   - Logistic regression was employed as a baseline classifier due to its simplicity and interpretability.

2. **Random Forest:**
   - Random forest was chosen for its ability to handle unbalanced datasets and its robustness against overfitting.

3. **Decision Tree:**
   - A decision tree classifier was also implemented to explore the interpretability of individual decision rules.

## Files

- `CreditCardFraudDetection.ipynb`: Jupyter notebook containing data preprocessing, undersampling, model training (logistic regression, random forest, decision tree), evaluation, and predictions.
- `creditcard.csv`: Sample dataset used in the notebook (replace with your actual dataset).

## Dependencies

Make sure you have the following libraries installed:

- Python 3.x
- NumPy
- Pandas
- Scikit-learn
- Matplotlib

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/CreditCardFraudDetection.git
   cd CreditCardFraudDetection
   ```

2. Install dependencies:

   ```bash
   pip install numpy pandas scikit-learn matplotlib
   ```

3. Open and run the Jupyter notebook:

   ```bash
   jupyter notebook CreditCardFraudDetectionb.ipynb
   ```

4. Follow the notebook instructions to:
   - Load and preprocess the dataset.
   - Perform undersampling of the majority class.
   - Train logistic regression, random forest, and decision tree classifiers.
   - Evaluate each model using appropriate metrics (accuracy, precision, recall, F1-score, etc.).
   - Compare and analyze the results.

## Results

- **Logistic Regression:** Accuracy Score : 93.68
- **Random Forest:** Accuracy Score: 93.15
- **Decision Tree:** Accuracy Score: 87.36

The results demonstrate the effectiveness of different classifiers in detecting credit card fraud, particularly after undersampling to mitigate class imbalance.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
