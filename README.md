# Patient Show/No-Show Prediction

A machine learning project to predict whether patients will attend their scheduled medical appointments or not show up. This prediction model helps healthcare providers optimize appointment scheduling, reduce waiting times, and improve resource allocation.



The notebook contains:
- Data loading and exploration
- Data preprocessing and cleaning
- Feature engineering
- Model training and evaluation
- Results visualization


## Project Structure

```
Patient-show-no_show-prediction-/
│
├── may25.ipynb              # Main analysis notebook
├── requirements.txt         # Python dependencies
├── README.md               # Project documentation
├── .gitignore              # Git ignore file
└── data/                   # (Add your dataset here)
```

## Methodology

### 1. Data Preprocessing
- Handling missing values
- Data type conversions
- Removing erroneous records (e.g., negative ages)
- Date/time feature extraction

### 2. Exploratory Data Analysis (EDA)
- Distribution analysis of features
- Correlation analysis
- No-show rate by different factors
- Visualization of key patterns

### 3. Feature Engineering
- Waiting time calculation (days between scheduling and appointment)
- Day of week extraction
- Age grouping
- Prior appointment history

### 4. Model Development
Potential models explored:
- Logistic Regression
- Decision Trees
- Random Forest
- Gradient Boosting (XGBoost, LightGBM)

### 5. Model Evaluation
Metrics used:
- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC
- Confusion Matrix


## Technologies Used

- **Python**: Primary programming language
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical computing
- **Scikit-learn**: Machine learning models and evaluation
- **Matplotlib/Seaborn**: Data visualization
- **Jupyter Notebook**: Interactive development environment

See `requirements.txt` for complete dependency list.


## Acknowledgments

- Dataset source: [Kaggle - Medical Appointment No Shows](https://www.kaggle.com/joniarroba/noshowappointments)
- Inspiration from similar healthcare analytics projects

---

**Note**: This project is for educational and research purposes.