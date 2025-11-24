# 📊 Lasso Path Explorer

A professional, interactive Streamlit application for understanding and visualizing Lasso Regression. This tool helps data scientists and students explore regularization paths, optimize hyperparameters, and compare different regression models.

## Features

- **📁 Data Management**: Upload your own CSV files or use built-in sample datasets (California Housing, Diabetes)
- **📈 Interactive Lasso Path**: Visualize how coefficients change as regularization strength increases
- **🎯 Cross-Validation Optimizer**: Automatically find the optimal alpha using LassoCV
- **🔮 Real-time Predictions**: Interactive interface to make predictions with live updates
- **⚖️ Model Comparison**: Compare Lasso, Ridge, and OLS side-by-side with comprehensive metrics

## Installation

1. Clone or download this repository
2. Install dependencies:
```bash
pip install -r requirements.txt
```

## Usage

Run the Streamlit app:
```bash
streamlit run app.py
```

The app will open in your default web browser at `http://localhost:8501`

## Deployment to Streamlit Cloud

1. Push your code to a GitHub repository
2. Go to [share.streamlit.io](https://share.streamlit.io)
3. Sign in with your GitHub account
4. Click "New app"
5. Select your repository and branch
6. Set the main file path to `app.py`
7. Click "Deploy"

## Requirements

- Python 3.8+
- Streamlit >= 1.28.0
- scikit-learn >= 1.3.0
- pandas >= 2.0.0
- numpy >= 1.24.0
- plotly >= 5.17.0

## How to Use

1. **Load Data**: Choose a sample dataset or upload your own CSV file
2. **Select Variables**: Choose your target variable and features from the sidebar
3. **Explore Lasso Path**: Navigate to the "Lasso Path" tab to see how coefficients change with regularization
4. **Find Optimal Alpha**: Use the "Cross-Validation" tab to find the best regularization parameter
5. **Make Predictions**: Use the "Predictions" tab to interactively make predictions
6. **Compare Models**: View the "Model Comparison" tab to see how Lasso compares to Ridge and OLS

## Educational Value

This app is designed to help users understand:
- How L1 regularization (Lasso) differs from L2 regularization (Ridge)
- The concept of regularization paths
- How cross-validation helps select optimal hyperparameters
- The trade-off between model complexity and generalization
- Feature selection through sparsity

## License

This project is open source and available for educational and portfolio purposes.
