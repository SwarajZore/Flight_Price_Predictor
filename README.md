# Flight Price Prediction

## Overview
This project aims to predict flight prices based on various input parameters such as airline, journey date, source, destination, and total stops. The prediction model is built using machine learning techniques, leveraging data preprocessing, feature engineering, and model training.

## Dataset
The dataset contains flight details including:
- Airline
- Date of Journey
- Source
- Destination
- Departure Time
- Arrival Time
- Duration
- Total Stops
- Price (Target Variable)

## Steps Involved
### 1. Data Preprocessing
- Import dataset from an Excel file.
- Handle missing values by dropping them.
- Convert `Date_of_Journey` into a timestamp format.
- Extract meaningful features from `Dep_Time`, `Arrival_Time`, and `Duration`.

### 2. Feature Engineering
- Convert categorical features (`Airline`, `Source`, `Destination`) using one-hot encoding.
- Process `Duration` to extract useful insights.

### 3. Model Training
- Split data into training and testing sets.
- Train machine learning models (e.g., Linear Regression, Decision Tree, Random Forest) to predict flight prices.
- Evaluate models using performance metrics like RMSE and R² score.

## Installation & Usage
### Prerequisites
Ensure you have the following installed:
- Python 3.x
- Jupyter Notebook
- Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn

### Steps to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/flight-price-prediction.git
   cd flight-price-prediction
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
4. Open `final.ipynb` and execute cells to preprocess data, train models, and make predictions.

## Results & Findings
- Analyzed how different features impact flight prices.
- Built and compared multiple machine learning models.
- Identified key factors affecting flight pricing trends.

## Future Improvements
- Enhance model accuracy using deep learning techniques.
- Integrate real-time flight data.
- Build a web interface for user-friendly predictions.



