* Sheti Mitra – Smart Agriculture Decision Support System

Sheti Mitra is a machine learning–based agriculture support system designed to help farmers make data-driven decisions by predicting crop yield, market price, and recommending alternate crops.  
The system focuses on practical usability by delivering prediction reports directly via WhatsApp.



 Problem Statement

Farmers often face crop losses due to:
- Uncertain weather conditions  
- Poor soil health awareness  
- Unpredictable market prices  

Sheti Mitra addresses these challenges using data analytics and machine learning.



 Solution Overview

- Predicts crop yield using soil and weather parameters  
- Estimates crop market price using historical data  
- Suggests alternate crops for better profitability  
- Generates farmer-friendly reports and sends them via WhatsApp  
- Generated reports will be stored in the reports/ directory at runtime.



 Technologies & Tools

- Language: Python  
- Machine Learning:  
  - Random Forest (Crop Yield Prediction)  
  - Linear Regression (Crop Price Prediction)  
- Libraries: Pandas, NumPy, Scikit-learn, Matplotlib  
- Automation: PyWhatKit (WhatsApp integration)  
- IoT (Optional): Arduino (Soil Moisture Sensor)  
- Version Control: Git & GitHub  



 System Architecture (Flow)

1. User inputs crop, soil, and location details  
2. Weather parameters are fetched from dataset  
3. ML models process data and generate predictions  
4. Report image is generated automatically  
5. Report is sent to the farmer via WhatsApp  

---

 Project Structure

sheti-mitra/
│
├── src/ # Core ML & application logic
├── data/ # Datasets (CSV / Excel)
├── reports/ # Sample prediction outputs
├── hardware/ # Arduino soil sensor code
├── README.md
├── .gitignore
└── LICENSE

 Key Features

- Crop yield prediction (Low / Medium / High)  
- Market price estimation (₹ / quintal)  
- Alternate crop recommendation  
- Soil health analysis (N, P, K, pH)  
- WhatsApp-based report delivery  



 Machine Learning Models

 🔹 Random Forest
- Handles non-linear agricultural data  
- High accuracy for yield prediction  

🔹 Linear Regression
- Used for market price trend estimation  
- Lightweight and interpretable  



 How to Run

bash
git clone https://github.com/Rutukhemnar/Sheti-Mitra-2.0.0
pip install -r library.txt
python src/MainGUI.py*
