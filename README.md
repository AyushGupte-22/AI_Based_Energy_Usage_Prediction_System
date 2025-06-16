
# 🔋 AI-Based Energy Usage Prediction System

This capstone project presents an **AI-powered solution** to predict household energy consumption using **LSTM (Long Short-Term Memory)** neural networks. The system is designed to enhance energy efficiency and provide actionable insights for smart energy management across different zones of a household.

---

## 🚀 Live App

👉 [Click here to try the app](https://aibasedenergyusagepredictionsystem-devanshusawarkar.streamlit.app/)  

![image_1](https://github.com/user-attachments/assets/2b24ca47-5cb9-45e5-b476-795e36d08d57)

---

## 🔍 Project Overview

The system utilizes historical power consumption data to forecast energy usage in three primary household zones:

- ❄️ **AC/Heater Zone**
- 🍳 **Kitchen Appliances**
- 🧺 **Laundry Appliances**

Predictions are made using separate **LSTM models** trained on the *Individual Household Electric Power Consumption* dataset. The app is built using **Streamlit** for a clean, interactive UI.

---

## 🧠 Key Features

- 🔮 LSTM-based deep learning models for time series prediction  
- 📊 Zone-wise prediction for targeted energy management  
- 📈 Real-time visualization of actual vs predicted usage  
- 🚨 Usage threshold alerts to detect abnormal consumption  
- 🌱 Energy-saving tips based on appliance behavior  
- 🌐 Streamlit-based intuitive web interface  

---

## 🗂️ Project Structure

```
AI_Based_Energy_Usage_Prediction_System/
│
├── dataset/                           # Raw data folder
│   └── household_power_consumption.txt
│
├── app.py                             # Streamlit app script
├── lstmmodel.ipynb                    # Jupyter notebook for training models
├── model_kitchen.h5                   # Pretrained LSTM model for kitchen
├── model_laundry.h5                   # Pretrained LSTM model for laundry
├── model_ac_heater.h5                 # Pretrained LSTM model for AC/Heater
├── testing_energy_data.csv            # Sample test input
├── requirements.txt                   # Python package dependencies
└── README.md                          # This file
```

---

## ⚙️ How to Run the Project

1. **Clone the repository**
```bash
git clone https://github.com/AyushGupte-22/AI_Based_Energy_Usage_Prediction_System.git
cd AI_Based_Energy_Usage_Prediction_System
```

2. **Create and activate a virtual environment**
```bash
python -m venv venv

# Activate the virtual environment
# On Windows:
venv\Scripts\activate

# On Mac/Linux:
source venv/bin/activate
```

3. **Install all dependencies**
```bash
pip install -r requirements.txt
```

4. **Run the Streamlit application**
```bash
streamlit run app.py
```

---

## 🧪 Model Training

If you wish to retrain the LSTM models with custom data:

- Open `lstmmodel.ipynb` in Jupyter Notebook or VS Code.
- Follow the step-by-step instructions to:
  - Preprocess the dataset
  - Create time series sequences
  - Train LSTM models
  - Save models as `.h5` files

---

## 📊 Dataset Used

The system uses the [Individual Household Electric Power Consumption Dataset](https://archive.ics.uci.edu/ml/datasets/individual+household+electric+power+consumption) from the **UCI Machine Learning Repository**.

**Attributes include**:
- `Sub_metering_1`: Kitchen
- `Sub_metering_2`: Laundry room
- `Sub_metering_3`: AC/Heater

---

## 🚀 Future Enhancements

- 🔄 **Integration with IoT sensors** for real-time data streams  
- ☁️ **Deployment** on cloud platforms (AWS, GCP, Streamlit Cloud)  
- 🧠 Add **model explainability** with SHAP or Grad-CAM  
- 📱 Build a **responsive mobile UI** for remote energy tracking  
- 🛠️ Add an **ML-powered recommendation engine** for energy-saving suggestions  

---

## 👨‍💻 Authors

Built by the Capstone Team of **Symbiosis Institute of Technology, Nagpur**:

- Devanshu Sawarkar  
- Pratham Agrawal  
- Devansh Motghare  
- Pradyumn Waghmare  
- Ayush Gupte  

---

## 📄 License

This project is licensed under the **MIT License**.  
See the [LICENSE](LICENSE) file for more details.

---

## 🙏 Acknowledgements

- [UCI Machine Learning Repository](https://archive.ics.uci.edu/)
- [Streamlit](https://streamlit.io/)
- [Keras + TensorFlow](https://keras.io/)
- [Scikit-learn](https://scikit-learn.org/)
