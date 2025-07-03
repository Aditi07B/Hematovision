# 🩸 Hematovision

**Hematovision** is an AI-powered Flask web app that classifies microscopic blood cell images based on the type of **white blood cells (WBCs)** detected. This tool can support early detection of certain blood conditions — though it's not for professional use (yet) due to current model accuracy.

> ⚠️ Note: The current model is a basic CNN and does not replace medical diagnosis. Improvements are on the roadmap.

---

## 💡 Features

- Upload blood cell microscope images
- Detect WBC types using a TensorFlow model
- Flask-powered web UI
- Real-time prediction on uploaded images

---

## 🛠️ Tech Stack

- **Python 3.9**
- **TensorFlow + Keras**
- **Flask**
- **Pillow** (for image preprocessing)
- **HTML/CSS** (basic frontend)

---

## 🚀 Getting Started (Run It Locally)

### 🧱 Step-by-step setup:

#### 1. Clone this repository:

git clone https://github.com/Aditi07B/Hematovision/tree/main
cd Hematovision
#### 2️. Create and activate a virtual environment

python -m venv tf_venv
.\tf_venv\Scripts\activate     # For Windows

##### (If on macOS/Linux, use: source tf_venv/bin/activate)


#### 3️. Install the required dependencies

pip install -r requirements.txt

##### (Optional) If you don’t have requirements.txt yet:
pip freeze > requirements.txt


#### 4️ Run the Flask app

python app.py

##### Then open http://127.0.0.1:5000 in your browser
