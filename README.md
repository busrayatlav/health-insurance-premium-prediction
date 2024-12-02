# Health Insurance Premium Prediction

## Overview
This project predicts the premium amount of a health insurance policy based on various factors like age, BMI, smoking habits, and region. The model is built using Python and leverages **Random Forest Regression**, which is identified as the best-performing algorithm for this task.

---

## Dataset
The dataset contains the following features:
- **age**: The age of the person.
- **sex**: Gender of the person (male/female).
- **bmi**: Body Mass Index of the person.
- **children**: Number of children the person has.
- **smoker**: Whether the person smokes or not (yes/no).
- **region**: The region where the person lives.
- **charges**: The premium amount of the insurance policy (target variable).

### Source
The dataset is publicly available on Kaggle.

---

## Installation

### Step 1: Clone the Repository
```
git clone https://github.com/yourusername/health-insurance-premium-prediction.git
cd health-insurance-premium-prediction
```

---

## Project Workflow

### 1. Data Preprocessing
- The dataset is loaded and checked for missing values.
- Categorical features like `sex` and `smoker` are encoded into numerical values.

### 2. Exploratory Data Analysis (EDA)
- Visualizations are used to analyze the distribution of smokers and regional populations.
- Correlation between features is calculated to understand their impact on the premium amount.

### 3. Model Training
- The data is split into training and testing sets.
- A **Random Forest Regressor** is used to train the model.

### 4. Predictions
- The model predicts the premium amount for the test data.
- Predicted values are compared with the actual values for evaluation.

---

## Usage

### Running the Project
1. Open the terminal in the project directory.
2. Run the following script to execute the code:
   ```
   python health_insurance_premium_prediction.py
   ```
3. The script will output the predicted premium amounts for test cases.

---

## Results

The **Random Forest Regression** model performs well in predicting health insurance premiums.

### Example Output:
```
Predicted Premium Amount
0              11331.111753
1               5366.132261
2              28257.205036
3               9793.356425
4              34720.204296
```

---

## Dependencies

- Python 3.7+
- Pandas
- NumPy
- Matplotlib
- Plotly
- Scikit-learn

---

## Future Improvements

- Include additional features like pre-existing health conditions for better predictions.
- Experiment with advanced regression models or ensemble techniques.
- Deploy the model as a web application using Flask or Streamlit.

---

## Contributing

Contributions are welcome! Feel free to submit a pull request or open an issue for suggestions or improvements.

---

## License

This project is licensed under the [MIT License](LICENSE).

---

## Acknowledgements

- **Dataset**: Sourced from Kaggle.
- **Inspiration**: Inspired by Aman Kharwal's article.
- **Libraries and Tools**: Built using Python, Pandas, Plotly, and Scikit-learn.

---

## Repository Structure

```
health-insurance-premium-prediction/

│

├── health_insurance_premium_prediction.py   # Main Python script for the project

├── Health_insurance.csv                     # Dataset file

├── requirements.txt                         # List of required libraries

├── README.md                                # Project documentation

└── LICENSE                                  # License file

```
