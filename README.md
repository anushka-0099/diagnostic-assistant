## AI-Powered Diagnostic Assistant

📌 Overview

The AI-powered diagnostic assistant is an integrated platform that assists healthcare professionals by leveraging AI for medical image analysis, symptom-based disease prediction, and an AI chatbot. This solution aims to improve efficiency, reduce diagnostic time, and enhance patient care.

🚀 Features

🔬 Medical Image Analysis

✅ CT-to-MRI Conversion: Uses Pix2Pix GAN to generate MRI-like images from CT scans.
✅ Chest X-ray Disease Classification: Implements ResNet-50 to detect pneumonia and other diseases from X-ray images.

🏥 Symptom-Based Disease Prediction

✅ Utilizes Machine Learning models (Decision Trees, XGBoost, Random Forest, ANN) for early disease prediction.
✅ Based on public medical datasets, ensuring accuracy and reliability.

💬 AI Chatbot (Google AI Studio - Dialogflow)

✅ Provides preventive measures, symptom assessment, and health recommendations.
✅ Helps patients and doctors with disease-related queries and guidance.

🛠 Tech Stack

Deep Learning: TensorFlow/Keras, PyTorch

Machine Learning: Scikit-learn, Pandas, NumPy

Medical Imaging: OpenCV, PIL

Backend API: Flask

Chatbot: Google AI Studio (Dialogflow)

📊 Dataset

📌 Chest X-ray Dataset for pneumonia classification. https://www.kaggle.com/datasets/alifrahman/chestxraydataset/data
📌 CT-MRI paired datasets for image translation. https://www.kaggle.com/datasets/darren2020/ct-to-mri-cgan/data
📌 Public symptom-disease datasets (Kaggle) for symptom-based diagnosis. https://www.kaggle.com/datasets/kaushil268/disease-prediction-using-machine-learning

🔧 Installation & Setup

✅ Prerequisites

Python 3.8+

TensorFlow, PyTorch

Flask, NumPy, Pandas

Google AI Studio account

🚀 Steps

1️⃣ Clone the repository:

git clone https://github.com/yourusername/AI-Diagnostic-Assistant.git
cd AI-Diagnostic-Assistant

2️⃣ Install dependencies:

pip install -r requirements.txt

3️⃣ Run the Flask API for medical image analysis:

python app.py

4️⃣ Deploy chatbot on Google AI Studio (Instructions in docs/chatbot_setup.md)


