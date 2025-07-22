# 🐔 Poultry Disease Classifier Web App

A lightweight deep learning-powered Flask web application to **detect poultry diseases** from chicken images using **transfer learning with VGG16**.

---

## 🚀 Features

- 🧠 Pre-trained VGG16 model
- 🔍 Classifies into 4 categories:
  - **Coccidiosis**
  - **Healthy**
  - **Newcastle Disease (NCD)**
  - **Salmonella**
- 🖼 Upload an image and get predictions in real time
- 🌐 Flask web app with clean UI

---

## 📁 Folder Structure

```
poultry_disease_classifier/
│
├── models/
│   └── poultry_disease_model.h5      # Trained model
│
├── templates/
│   └── index.html                    # Webpage template
│
├── static/                          # (Optional) CSS/images
│
├── app.py                           # Flask app
├── model_training.py                # Script to train model
└── README.md                        # Project description
```

---

## 🧑‍💻 How to Run on Your Device

### 1️⃣ Install Python (if not already installed)

> Download from [https://www.python.org/downloads/](https://www.python.org/downloads/)  
> ✅ Make sure to **check "Add Python to PATH"** during installation.

---

### 2️⃣ Install Required Packages

Open terminal or command prompt:

```bash
pip install tensorflow flask pillow
```

Alternatively, create a `requirements.txt` and use:

```bash
pip install -r requirements.txt
```

---

### 3️⃣ Run the App

```bash
cd path\to\poultry_disease_classifier
python app.py
```

Visit in browser: [http://127.0.0.1:5000](http://127.0.0.1:5000)

---

## 💡 How to Use

1. Upload a **chicken image**
2. Click on **"Predict"**
3. The model will display the detected disease

---

## 🛠 Technologies Used

- TensorFlow / Keras
- Transfer Learning (VGG16)
- Flask (Python Web)
