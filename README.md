
# Housing Price Prediction with Scikit-Learn

## 📘 Project Overview
This project demonstrates how to build a machine learning model using Python and scikit-learn to predict housing prices based on various features from a California housing dataset.

## 📊 Dataset Description
The dataset (`housing.csv`) contains information about housing in California, including:
- `longitude`, `latitude`: Location coordinates
- `housing_median_age`: Median age of houses
- `total_rooms`, `total_bedrooms`: Room statistics
- `population`, `households`: Demographic data
- `median_income`: Median income of households
- `median_house_value`: Target variable (house price)
- `ocean_proximity`: Categorical feature indicating proximity to the ocean

## ⚙️ Installation
To run this project, install the required Python packages:
```bash
pip install pandas scikit-learn
```

## 🚀 Usage Instructions
### Option 1: Run Locally
1. Place `housing.csv` in your working directory.
2. Run the Python script provided in this repository.

### Option 2: Run in Google Colab
1. Open [Google Colab](https://colab.research.google.com/).
2. Upload `housing.csv` using the file upload button.
3. Paste and run the provided Python code.

## 🧠 Model Details
- **Model Used**: `RandomForestRegressor`
- **Features Used**:
  - `housing_median_age`, `total_rooms`, `total_bedrooms`, `population`, `households`, `median_income`, `ocean_proximity`
- **Target**: `median_house_value`

## 📈 Evaluation Metrics
- **R² Score**: Measures how well the model explains the variance in the target.
- **Mean Absolute Error (MAE)**: Average absolute difference between predicted and actual values.

## ✅ Results
- **R² Score**: ~0.7158
- **MAE**: ~$43,367.13

## 📂 File Structure
```
├── housing.csv
├── model_script.py
├── README.md
```

## 📬 Contact
For questions or suggestions, feel free to reach out!
