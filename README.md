# Diamond Price Prediction



📌 Overview

The Diamond Price Prediction project is a machine learning-based application that predicts the price of diamonds based on various features such as carat, cut, color, clarity, and dimensions. This project follows a modular pipeline approach, ensuring efficiency and scalability for data processing, model training, and deployment.

✨ Features

🚀 End-to-End Pipeline: Includes data ingestion, transformation, model training, and prediction.

🌐 Flask Web App: A user-friendly interface for predicting diamond prices.

📂 Modular Code Structure: Organized components for better maintainability.

🛠 Logging & Exception Handling: Ensures robust debugging and error tracking.

📌 Deployment Ready: Can be deployed using Flask.

📁 Project Structure
![structure](https://github.com/user-attachments/assets/cb4637ed-6c40-4f2b-98da-14f1c1b13bf4)


🔧 Installation & Setup

Clone the repository:

git clone https://github.com/Shadabsam/DiamondPricePrediction.git
cd DiamondPricePrediction

Create a virtual environment and activate it:

conda create --name dp python=3.12 -y
conda activate dp

Install dependencies:

pip install -r requirements.txt

Run the training pipeline:

python src/pipelines/training_pipeline.py

Start the Flask web application:

python application.py

🚀 Usage

Open the web application in your browser (http://127.0.0.1:5000/).

Enter diamond attributes in the form and get the predicted price.

🛠 Technologies Used

Python (pandas, NumPy, scikit-learn, Flask)

Machine Learning (Regression models for price prediction)

Web Framework (Flask for deployment)
