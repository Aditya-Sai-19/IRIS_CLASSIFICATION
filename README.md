# 🌸 Iris Flower Classification Web App

A simple web application that predicts the species of an **Iris flower** (*Setosa*, *Versicolor*, or *Virginica*) based on its sepal and petal measurements.  
This project uses a **Decision Tree Classifier** model trained with **Scikit-learn** and served via a **Flask** backend.

---

## 🚀 Deployed Application
**Live URL:** [Iris Flower Classification Web App](https://iris-classification-i93t.onrender.com/)

---

## ✨ Features
- **Interactive UI:** A clean and user-friendly interface for inputting flower measurements.
- **Real-time Prediction:** Instantly classifies Iris species using a pre-trained ML model.
- **Dynamic Feedback:** Highlights and displays the predicted flower species card for better UX.
- **RESTful API:** A `/predict` endpoint to get predictions programmatically.
- **Responsive Design:** Fully functional on both desktop and mobile devices.

---

## 🛠 Technology Stack
- **Backend:** Python, Flask, Gunicorn  
- **Machine Learning:** Scikit-learn, NumPy, Pandas  
- **Frontend:** HTML, CSS, JavaScript (Fetch API)

---

## ⚙️ Setup and Installation
To run this project locally:

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/Aditya-Sai-19/your-repo-name.git
cd your-repo-name
```

### 2️⃣ Create and Activate Virtual Environment
**For Windows:**
```bash
python -m venv venv
venv\Scripts\activate
```
**For macOS/Linux:**
```bash
python3 -m venv venv
source venv/bin/activate
```

### 3️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

---

## ▶️ How to Run
### Using Flask Development Server:
```bash
flask run
```
The app will be available at **http://127.0.0.1:5000**

### Using Gunicorn (Production-like):
```bash
gunicorn app:app
```

---

## 📡 API Endpoint
**URL:** `/predict`  
**Method:** `POST`  

### **Form Data:**
- `sepal_length` (float)  
- `sepal_width` (float)  
- `petal_length` (float)  
- `petal_width` (float)

**Success Response:**
```json
{
  "prediction": "Iris-setosa"
}
```

---

## 📂 File Structure
```
├── app.py                  # Main Flask application
├── saved_model.sav         # Pre-trained Decision Tree model
├── requirements.txt        # Python dependencies
├── runtime.txt             # Python version for deployment
├── templates/
│   └── index.html          # Frontend HTML
└── static/
    └── *.jpg               # Images for the UI
```

---

## 👨‍💻 Author
**Aditya Sai**  
- **GitHub:** [@Aditya-Sai-19](https://github.com/Aditya-Sai-19)  
- **LinkedIn:** [aditya-sai-3317702a6](https://www.linkedin.com/in/aditya-sai-3317702a6/)

---

## ⭐ Contribute
If you like this project, feel free to **star** ⭐ the repo and fork it for contributions.
