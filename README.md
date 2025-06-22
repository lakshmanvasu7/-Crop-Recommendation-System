# 🌿 Cropify: Smart Crop Recommendation System

Cropify is a machine learning-powered web application that provides farmers and agriculturists with precise crop recommendations based on soil and weather parameters. The goal is to maximize yield and ensure sustainable agricultural practices using data-driven insights.

---

## 📈 Features

* Predicts the best-suited crop to grow based on:

  * Nitrogen (N), Phosphorus (P), Potassium (K)
  * Temperature, Humidity
  * Soil pH, Rainfall
* Easy-to-use Flask web interface
* Built using a trained Random Forest model
* Clean UI with integrated crop insights and descriptions

---

## 📚 Tech Stack

* **Frontend**: HTML, CSS, Bootstrap
* **Backend**: Python, Flask
* **ML Model**: Random Forest Classifier (scikit-learn)
* **Data**: [Crop Recommendation Dataset](https://www.kaggle.com/datasets)

---

## 🚀 Getting Started

### Prerequisites

Make sure you have Python 3.7+ installed.

### Installation

```bash
# Clone the repository
git clone https://github.com/lakshmanvasu7/Cropify.git
cd Cropify

# Create virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows

# Install dependencies
pip install -r requirements.txt
```

### Run the Application

```bash
python app.py
```

Navigate to `http://127.0.0.1:5000` in your browser.

---

## 📂 Project Structure

```
Cropify/
├── app.py                     # Flask application
├── logo_cropify.png           # Project logo
├── requirements.txt           # Required packages
├── README.md                  # Project documentation
├── Dataset/
│   ├── Crop_Desc.csv          # Descriptions of crops
│   └── Crop_recommendation.csv # Training dataset
├── Model/
│   └── RDF_model.pkl          # Trained Random Forest model
└── MAN 206 Project_...ipynb   # Project notebook
```

---

## 🖼️ Screenshots 
![Screenshot 2025-06-22 115734](https://github.com/user-attachments/assets/5edf7235-4fa7-4233-be15-a1be622d9712)


> *Add screenshots of the web interface here.*

---

## 👥 Authors & Contributors

* **Bernardino**
* **Digan**
* **Esguerra**

Special thanks to the contributors and the open-source community.

---

## ✉️ Contact

For any questions, suggestions, or feedback:

* GitHub: [lakshmanvasu7](https://github.com/lakshmanvasu7)
* Email: [vaasu.a3aa@gmail.com](mailto:vaasu.a3aa@gmail.com)

---

## ✉️ License

This project is licensed under the MIT License.
