# Profit-Prediction Machine Learning Model

Overview

This project predicts the profit percentage for baked goods based on selling price, cost details, and packaging cost. The model uses a Random Forest Regressor and provides insights into profit trends.

Features

Machine Learning Model: Uses a Random Forest Regressor to predict profit percentage.

Power BI Integration: Generates CSV output for Power BI visualizations.

Interactive UI: A Gradio-based web app for real-time profit prediction.

Performance Evaluation: Computes MAE and R2 Score.

Project Structure

profit-prediction/
│── data/                # (Optional) Store datasets
│── notebooks/           # Jupyter notebooks for analysis (if any)
│── model/               # Save trained model (profit_model.pkl)
│── src/                 # Python scripts for training and predictions
│── PowerBI/             # Power BI report files (.pbix)
│── README.md            # Project description and usage instructions
│── requirements.txt     # Dependencies
│── profit_predictions.csv  # Model output for Power BI
│── app.py               # Gradio web app for profit prediction

Installation

1. Clone the Repository

git clone https://github.com/your-username/profit-prediction.git
cd profit-prediction

2. Install Dependencies

pip install -r requirements.txt

Usage

1. Train the Model

Run the following script to train the model:

python src/train_model.py

2. Run the Prediction Web App

python app.py

This launches a Gradio-based UI where users can enter product details and get profit predictions.

3. Generate Power BI Reports

Open Power BI Desktop.

Load the profit_predictions.csv file.

Use charts like Profit Analysis, Cost Breakdown, and Revenue vs. Cost Comparison to analyze trends.

Model Performance

The model is evaluated using:

Mean Absolute Error (MAE): Measures prediction accuracy.

R2 Score: Indicates how well the model explains variance in profit.

Contribution

Feel free to fork this repository and submit pull requests for improvements.


