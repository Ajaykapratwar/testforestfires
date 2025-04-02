### 🔥 **Algerian Forest Fire Prediction - Ridge Regression Flask App**  

This project is a **Machine Learning-based Flask Web App** that predicts **Fire Weather Index (FWI)** using **Ridge Regression**. The model is trained using **scikit-learn**, and the application is built using **Flask**.  

---

## 📌 **Project Overview**  


- The **model** is trained to predict **FWI** based on environmental factors like temperature, humidity, wind speed, and rainfall.  
- The **Flask web app** allows users to input data and get predictions.  
- The **model uses Ridge Regression**, which helps in reducing overfitting.  

---

## 🛠 **Technologies Used**  

- **Python** (pandas, numpy, scikit-learn)  
- **Flask** (for web app)  
- **HTML, CSS** (for frontend)  
- **Pickle** (for model serialization)  

---

## 🚀 **How to Run the Project?**  

### **1️⃣ Clone the Repository**  
```bash
git clone https://github.com/Ajaykapratwar/testforestfires.git
cd testforestfires
```

### **2️⃣ Create a Virtual Environment (Optional but Recommended)**  
```bash
python -m venv venv
source venv/bin/activate  # On macOS/Linux
venv\Scripts\activate  # On Windows
```

### **3️⃣ Install Dependencies**  
```bash
pip install -r requirements.txt
```

### **4️⃣ Run the Flask Application**  
```bash
python application.py
```

- The application will start at **http://127.0.0.1:5000/**.  
- Enter the required inputs and get the predicted **FWI value**.

---

## 📂 **Project Structure**  

```
📂 testforestfires
│── models/                      # Trained models (ridge.pkl, scaler.pkl)
│── templates/                   # HTML templates (index.html, home.html)
│── application.py               # Flask web application
│── notebook/                    # Jupyter Notebook for model training and model comparison
│── requirements.txt             # Python dependencies
│── README.md                    # Project Documentation
```

---

## 📊 **Dataset**  
The model is trained on a dataset containing various environmental parameters affecting forest fires. The key features include:  

- **Temperature**  
- **Relative Humidity (RH)**  
- **Wind Speed (Ws)**  
- **Rainfall (Rain)**  
- **Fine Fuel Moisture Code (FFMC)**  
- **Duff Moisture Code (DMC)**  
- **Initial Spread Index (ISI)**  
- **Classes (Fire Category)**  
- **Region**  

---

## 💡 **Future Improvements**  

- ✅ Deploying the app on **AWS / Heroku**.  
- ✅ Adding more machine learning models like **Lasso, Decision Trees, Random Forest**.  
- ✅ Improving **frontend design** for better user experience.  

---

## 🤝 **Contributing**  
If you’d like to contribute, feel free to fork the repository and submit a **pull request**.  

---

## 📜 **License**  
This project is **open-source** and available under the **MIT License**.  
