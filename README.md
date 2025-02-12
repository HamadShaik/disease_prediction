Disease Prediction System Overview This is a machine learning-based disease prediction system that predicts whether a person has diabetes, heart disease, or Parkinson’s disease based on user input. The system is built using Streamlit for the frontend and ML models for prediction.

📁 Project Structure Disease-Prediction/ │── datasets/ │ ├── diabetes.csv │ ├── heart.csv │ ├── parkinsons.csv 
│── training_modules/ │ ├──diabetes.ipynb and diabetes_model.sav │ ├──heartdisease.ipynb and heart_model.sav │ ├── parkinsons.ipynb and parkinson.sav (files of code of disease predction using ML models) |── web.py │── README.md |── requirements.txt

🛠 Technologies Used Python 🐍 Streamlit (for UI) Scikit-learn (for model training) Pandas & NumPy (for data processing) Pickle (for model storage) ⚡ Features ✔ Predicts Diabetes, Heart Disease, and Parkinson’s Disease ✔ User-friendly Streamlit interface ✔ Models trained on real-world datasets ✔ Fast and accurate results

🚀 How to Run 
1️⃣ Clone the repository: https://github.com/HamadShaik/disease_prediction 
      --> cd Disease-Prediction

2️⃣ Install dependencies: pip install -r requirements.txt

3️⃣ Run the application: streamlit run web.py

4️⃣ Enter the required details and get predictions!

📊 How It Works User inputs health parameters Pre-trained ML models process the data Prediction is displayed on the UI

🏗 Future Improvements Add more diseases Improve accuracy with advanced models Deploy on cloud platforms

# disease_prediction
