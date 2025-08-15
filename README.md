# House Price Prediction 🏠📈

This project predicts house sale prices using machine learning. It is based on a dataset containing various features like lot size, number of rooms, year built, and more.

## 📂 Project Structure

- `house_price_predict.ipynb` — Main Jupyter Notebook containing data cleaning, EDA, feature engineering, and model training
- `output.csv` — Predicted house prices for the test dataset
- `requirements.txt` — Python dependencies
- `data/` — Folder containing datasets (ignored in `.gitignore`)

## ⚙️ Installation

### 1. Clone the repository
```bash
git clone https://github.com/your-username/house-price-prediction.git
cd house-price-prediction
```

### 2. Create a virtual environment
```bash
python -m venv venv
```

### 3. Activate the virtual environment

**Linux / Mac:**
```bash
source venv/bin/activate
```

**Windows:**
```bash
venv\Scripts\activate
```

### 4. Install dependencies
```bash
pip install -r requirements.txt
```

## 🚀 Usage

### Open the Jupyter Notebook
```bash
jupyter house_price_predict
```

Then run all cells to reproduce the model training and prediction.

## 📊 Model

- **Algorithm:** XGBoost Regressor
- **Evaluation Metric:** Mean Squared Error (MSE)
- **Cross-Validation:** Used to validate performance on unseen data

## 📌 Notes

- Predictions are stored in `output.csv`

## 👨‍💻 Author

Fratsa Islam Yacine