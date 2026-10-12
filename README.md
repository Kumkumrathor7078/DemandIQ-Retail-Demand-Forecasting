# DemandIQ: Intelligent Retail Demand Forecasting

**DemandIQ** is a machine learning project that analyzes retail demand data and compares regression models to understand and predict product demand using historical retail information.

## Project Highlights

- Analyzed **169,211 retail records**.
- Explored product, warehouse, promotional, and time-based features.
- Engineered date-based features to capture temporal patterns.
- Implemented and compared Linear Regression and Random Forest models.
- Evaluated model performance using MAE, RMSE, and R² score.

## Tech Stack

- **Language:** Python
- **Data Analysis:** Pandas, NumPy
- **Machine Learning:** Scikit-learn
- **Models:** Linear Regression, Random Forest Regressor

## Methodology

1. **Data Preparation** — Loaded and inspected the dataset, including missing-value and duplicate checks.
2. **Feature Engineering** — Extracted Year, Month, Day, Day of Week, and Is Weekend from the date column.
3. **Preprocessing** — Encoded categorical variables for model training.
4. **Model Development** — Trained Linear Regression and Random Forest regression models.
5. **Evaluation** — Compared predictions using MAE, RMSE, and R² score.

## Evaluation Metrics

| Metric | Purpose |
|---|---|
| MAE | Measures average absolute prediction error |
| RMSE | Gives greater weight to larger prediction errors |
| R² Score | Measures how well the model explains variation in demand |

## Key Learnings

- Data preprocessing and exploratory analysis
- Date-based feature engineering
- Regression model implementation
- Model evaluation and comparison

## Future Enhancements

- Perform hyperparameter tuning.
- Improve feature selection.
- Evaluate models with a strict chronological train-test split.

## Author

**Kumkum Rathor**  
M.Sc. Applied Mathematics  
National Institute of Technology, Warangal
