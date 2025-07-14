# smart-stp-ai
Smart Sewage Treatment Plant (STP) Dashboard using AI | Streamlit App  This AI-powered STP monitoring dashboard predicts treated water quality parameters like BOD, COD, TSS, and pH using machine learning. It features real-time pH integration, motor automation scheduling, chlorination dose calculation, QR/mobile etc
# 💧 Smart STP AI Dashboard

A professional AI-powered dashboard for monitoring, predicting, and controlling Sewage Treatment Plant (STP) operations.

## 🚀 Features

- ✅ Live pH sensor integration (via Flask)
- 🔮 AI-based predictions for:
  - BOD (Biological Oxygen Demand)
  - COD (Chemical Oxygen Demand)
  - TSS, pH, Ammonical Nitrogen, Total Nitrogen
- ⚙️ Smart Motor Runtime Scheduling (based on flow + pollution)
- 🧪 Chlorination Quantity Calculation (in mL for 1000L batch)
- 🗣️ Voice Assistant (via pyttsx3)
- 📡 Twilio SMS alerts for unsafe conditions
- 📈 Historical CSV upload for filtering, stats & trend graph
- 📱 QR Code generation + mobile access
- 📤 Report generation & CSV logging

## 🧠 Model

- Trained with supervised machine learning on real wastewater parameters
- `trained_model.pkl` must be in root folder for prediction

## 🔧 Tech Stack

- `Python`, `Streamlit`, `scikit-learn`, `pandas`, `qrcode`, `pyttsx3`, `twilio`
- Frontend & backend fully integrated in one Streamlit app

## 📦 Files to Include

| File                     | Purpose                          |
|--------------------------|----------------------------------|
| `app_full_final_expert_stp.py` | Main app logic                |
| `trained_model.pkl`      | Trained ML model                 |
| `requirements.txt`       | Library dependencies             |

## 📂 Data Format for Upload

CSV with headers:

## 📡 Live App

👉 Deploy it easily via [Streamlit Cloud](https://streamlit.io/cloud)

---

Feel free to star ⭐ this repo if you find it useful, or fork to modify.


