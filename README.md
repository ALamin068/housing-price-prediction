# 🏡 Housing Price Prediction

This project builds a machine learning model to predict housing prices using the Kaggle House Prices dataset.

## 🚀 Tech Stack
- Python 3.12
- Pandas, NumPy, Matplotlib, Seaborn
- Scikit-Learn
- XGBoost
- Joblib

## 📁 Project Structure

housing-price-prediction/
├── data/ # Raw and processed datasets
├── model/ # Saved ML models and transformers
├── notebooks/ # Jupyter notebooks by stage
├── requirements.txt # Python dependencies
└── README.md # Project overview

bash
Copy
Edit

## 📊 Features
- EDA with Seaborn
- Data Cleaning
- Feature Engineering
- Model Training (Linear Regression, Random Forest, XGBoost)
- Evaluation (RMSE, R²)
- Final Prediction and Submission File

## 💡 How to Run

```bash
# Clone the repo
git clone https://github.com/your-username/housing-price-prediction.git
cd housing-price-prediction

# Create virtual environment (Mac)
python3 -m venv venv
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Run notebooks
jupyter notebook
