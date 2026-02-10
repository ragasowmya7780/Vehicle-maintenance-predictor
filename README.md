 🚗 Vehicle Maintenance Predictor

A Machine Learning-based web application that predicts whether a vehicle requires maintenance using sensor data.

📌 Overview

This project uses vehicle sensor readings to predict maintenance requirements before failure occurs.
It helps reduce unexpected breakdowns and improves vehicle reliability.

The application is built using:

* **Python**
* **Flask**
* **Scikit-learn**
* **HTML/CSS**

🎯 Objective

To develop a predictive maintenance system that:

* Uses sensor data for failure detection
* Applies machine learning for prediction
* Provides results through a web interface

---

## 🛠️ Technologies Used

* **Backend:** Python, Flask
* **Machine Learning:** Scikit-learn
* **Data Processing:** Pandas, NumPy
* **Frontend:** HTML, CSS
* **Model Storage:** Pickle

 ⚙️ How It Works

1. User enters vehicle sensor values.
2. Input data is scaled using a trained scaler.
3. Machine Learning model predicts:

   * Maintenance Required
   * No Maintenance Required
4. Result is displayed on the webpage.

## 🌐 Live Demo

🔗 https://vehicle-maintenance-predictor.onrender.com/


---

🚀 Installation & Setup

1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/vehicle-maintenance-predictor.git
cd vehicle-maintenance-predictor
```

2️⃣ Create Virtual Environment (Optional)

```bash
python -m venv venv
venv\Scripts\activate   # For Windows
```

3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

4️⃣ Run the Application

```bash
python app.py
```

Open in browser:

```
http://127.0.0.1:5000/
```

---

🔁 Model Training

To retrain the model:

```bash
python train.py
```

This will regenerate:

* `model.pkl`
* `scaler.pkl`

---

📊 Dataset

The dataset contains vehicle sensor readings such as:

* Engine Temperature
* Oil Pressure
* Vibration
* Speed
* Runtime

Target:

* Maintenance Required (Yes/No)

---

🌐 Deployment

The project can be deployed on platforms like:

* Render
* Heroku
* AWS
