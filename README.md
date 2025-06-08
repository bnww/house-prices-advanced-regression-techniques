# House Price Prediction Repository

## Overview
This repository contains code and notebooks for the **Ames Housing Price Prediction** project, a Kaggle competition aimed at predicting residential home sale prices in Ames, Iowa. It includes end-to-end workflows for data exploration, feature engineering, model training, and evaluation using advanced regression techniques.

## Repository Structure
```
HOUSE-PRICES-ADVANCED-REGRESSION-TECHNIQUES/
├── .history/                   # Notebook history logs
├── data_description.txt        # Dataset description and feature definitions
├── house_prices.ipynb          # Exploratory Data Analysis & Feature Engineering
├── rf.ipynb                    # Random Forest Model Pipeline
├── tfdf.ipynb                  # TensorFlow Decision Forests Pipeline
├── train.csv                   # Training dataset (79 features + SalePrice)
├── test.csv                    # Test dataset (79 features, without SalePrice)
├── sample_submission.csv       # Example submission format
├── submission.csv              # First model predictions
├── submission2.csv             # Second model predictions
└── README.md                   # Project documentation
```


## Usage
1. **Exploratory Data Analysis & Feature Engineering**
   - Open and run `notebooks/house_prices.ipynb` to explore the dataset and perform feature transformations.
2. **Model Training**
   - Run `notebooks/rf.ipynb` to train and evaluate a Random Forest regression model.
   - Run `notebooks/tfdf.ipynb` to train and evaluate a TensorFlow Decision Forests model.

## Key Features
- **Creative Feature Engineering**: Engineered meaningful variables from 79 raw predictors, handling missing values and encoding categoricals.
- **Advanced Regression Techniques**: Implemented and tuned ensemble models including Random Forest and Gradient Boosting (via TensorFlow Decision Forests).
- **Model Evaluation**: Achieved an RMSLE of **0.134** on the test set, placing in the top 7% of over 25,000 submissions.
- **Reproducible Pipelines**: Modular notebook workflows enabling easy adaptation and extension for further experimentation.

## Results & Insights
- **Best Model**: Gradient Boosting via TensorFlow Decision Forests
- **Metric**: Root Mean Squared Log Error (RMSLE) = 0.134
- **Ranking**: ~1700/25,000+ submissions

## Next Steps
- Explore additional feature interactions and polynomial features
- Integrate hyperparameter optimization (e.g., Optuna)
- Deploy a lightweight prediction service using FastAPI or Streamlit

## License
This project is released under the MIT License. See [LICENSE](LICENSE) for details.

## Contact
For questions or feedback, please open an issue or contact:
- **Name**: Your Name
- **Email**: your.email@example.com
- **GitHub**: [your-username](https://github.com/your-username)
