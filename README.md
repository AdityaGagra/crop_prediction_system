Crop Prediction System
A Machine Learning-powered application designed to assist farmers and agricultural enthusiasts in choosing the most suitable crop for their land. By analyzing soil nutrients and environmental conditions, the system provides data-driven recommendations to maximize yield.

🚀 Overview
This project uses a classification model to predict the best crop to grow based on several key parameters. The system is built with Python and utilizes a Flask web interface (via app.py) for easy user interaction.

📊 Key Features
Predictive Analysis: Recommends crops based on Nitrogen, Phosphorus, Potassium (NPK) levels, and weather data.

User Interface: A simple web form to input soil data and receive instant results.

Optimized Model: Uses a pre-trained model (model.pkl) and scaler for high accuracy.

📁 Project Structure
app.py: The core Flask application script.

crop_prediction_improved.ipynb: Jupyter Notebook detailing the data analysis and model training process.

Crop_recommendation.csv: The dataset containing historical crop growth data.

model.pkl: The saved machine learning model.

scaler.pkl & label_encoder.pkl: Files used for data normalization and category encoding.

requirements.txt: List of Python libraries required to run the project.

🛠️ Installation & Setup
1. Clone the Repository:
git clone https://github.com/AdityaGagra/crop_prediction_system.git
cd crop_prediction_system

2.Install Dependencies:
Make sure you have Python installed, then run:
pip install -r "requirements.txt"
3.Run the Application:
python app.py
Once running, open your browser and go to http://localhost:8501

🧪 Parameters Used for Prediction
To get a recommendation, the system requires:

Soil Nutrients: Nitrogen (N), Phosphorous (P), and Potassium (K) content.

Climate: Temperature (°C) and Humidity (%).

Soil Properties: pH value.

Rainfall: Total rainfall in mm.

📜 License
This project is licensed under the MIT License.
