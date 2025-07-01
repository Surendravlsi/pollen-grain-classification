# 🌼 Pollen Profiling: Automated Classification of Pollen Grains

This project uses a Convolutional Neural Network (CNN) to classify pollen grains into three categories: **Daisy**, **Sunflower**, and **Rose**. It includes a web-based user interface built with **Flask** to allow users to upload an image and get real-time predictions.

## 📁 Folder Structure

```
project/
├── app.py                     # Flask web application
├── train_model.py            # Script to train the CNN model
├── model/
│   └── pollen_model.h5       # Trained model
├── dataset/
│   ├── daisy/
│   ├── sunflower/
│   └── rose/
├── static/
│   ├── sample_inputs/        # Sample input images
│   ├── predictions/          # Output predictions saved here
│   └── css/style.css         # Web styling
├── templates/
│   └── index.html            # UI HTML page
├── requirements.txt
└── README.md
```
## 🚀 Features

- Trains a CNN model on a small pollen dataset.
- Flask web interface for uploading and classifying images.
- Static demo images and UI-ready structure included.
- Output prediction displayed in real time.
## 🧪 Dataset

A limited dataset is used for demonstration, containing:
- `daisy` (10 images)
- `sunflower` (10 images)
- `rose` (10 images)

You can expand this dataset with more real pollen grain images for better accuracy.
## 🛠️ Installation

1. **Clone this repository**:
   
   git clone https://github.com/Surendravlsi/pollen-grain-classification.git
   cd pollen-grain-separation
   

2. **Create a virtual environment (optional)**:
   
   python -m venv venv
   source venv/bin/activate 

3. **Install dependencies**:
  
   pip install -r requirements.txt

## 🧠 Train the Model

python train_model.py

This will create a trained model (`pollen_model.h5`) inside the `model/` directory.

## 🌐 Run the Flask App

python app.py

- Open your browser and go to `http://127.0.0.1:5000`

## ✅ Requirements

Install via `requirements.txt`, but key packages include:
- `tensorflow`
- `flask`
- `numpy`
- `Pillow`

## 👩‍🔬 Developed By
YAKASIRI JAHNAVI ,
SATHIGARI SURENDRA ,
SAGARLA MANOHAR ,
SAI RUPA ,
