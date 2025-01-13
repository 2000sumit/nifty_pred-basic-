
# Nifty Prediction

This project leverages Python and Machine Learning techniques to predict Nifty stock prices using historical data. The primary goal is to forecast the closing prices based on selected features and evaluate the model's performance.

---

## Features

- **Moving Average (MA9)**: A 9-day moving average of closing prices.
- Historical data columns: `Open`, `High`, `Low`, and `Close`.

---

## Technologies Used

- **Python**: For data processing, modeling, and visualization.
- **Pandas and NumPy**: For data manipulation and numerical operations.
- **Scikit-learn**: For scaling, splitting, and building the prediction model.
- **Matplotlib**: For data visualization.

---

## Dataset

The dataset contains historical Nifty stock market data with the following columns:
- `Date`: Date of the record.
- `Open`: Opening price.
- `High`: Highest price.
- `Low`: Lowest price.
- `Close`: Closing price.

Ensure the file is named `Nifty.csv` and located in the same directory as the script.

---

## Steps to Run the Project

1. Clone the repository or download the script.
2. Place the `Nifty.csv` file in the same directory as the script.
3. Install the required libraries:
   ```bash
   pip install pandas numpy scikit-learn matplotlib
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

Implementation Details
Data Preprocessing:

Handled missing values by dropping rows with NaN.
Computed a 9-day moving average (MA9) to smoothen the price fluctuations.
Feature Selection:

Chosen features: Open, High, Low, and MA9.
Target variable: Close.
Data Scaling:

Applied StandardScaler to normalize features for improved model performance.
Model Training and Evaluation:

Used Linear Regression for predictions.
Evaluated using:
Mean Squared Error (MSE).
R² Score.
Visualization:

Compared actual vs predicted closing prices through a line plot.
Results
Mean Squared Error (MSE): (Your output value here)
R² Score: (Your output value here)
The plot below visualizes the actual versus predicted prices.

Future Enhancements
Feature Engineering:
Include additional features like volume or other technical indicators.
Advanced Models:
Experiment with advanced algorithms like Random Forest, XGBoost, or LSTM.
Hyperparameter Tuning:
Optimize model parameters for better accuracy.
Data Augmentation:
Use data from multiple indices or time periods for robust modeling.
Visualization
The script generates a plot comparing actual vs predicted prices for intuitive understanding of the model's performance.


