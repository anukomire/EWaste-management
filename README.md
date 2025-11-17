# EWaste-management
C:\Users\Anusha\Downloads\ewaste> python sample.py



C:\Users\Anjali\Downloads\ewaste> streamlit run app.py 



🌱 Waste Classification AI
A intelligent waste classification system that uses deep learning to categorize waste materials into three environmental categories: Biodegradable, Recyclable, and Non-Recyclable. Built with a Flask backend and Streamlit frontend for seamless user experience.

https://img.shields.io/badge/AI-Waste%2520Classification-green
https://img.shields.io/badge/Python-3.8%252B-blue
https://img.shields.io/badge/TensorFlow-Deep%2520Learning-orange

🎯 Project Overview
This project addresses the growing challenge of waste management by providing an AI-powered solution that automatically classifies waste materials from images. The system helps users make informed decisions about proper waste disposal, promoting environmental sustainability.

Key Features
📸 Multiple Input Methods: Upload images or capture via camera

🎯 3-Category Classification: Biodegradable, Recyclable, Non-Recyclable

🔍 Material Detection: Identifies specific materials (paper, plastic, glass, etc.)

📊 Confidence Scoring: Visual confidence indicators for predictions

💾 Persistent Results: Session state management for seamless user experience

🎨 Professional UI: Modern, responsive interface with color-coded categories

🏗️ System Architecture
text
Waste Classification System
├── Backend (Flask API)
│   ├── MobileNetV2 Deep Learning Model
│   ├── Image Preprocessing Pipeline
│   ├── 3-Category Classification Logic
│   └── RESTful API Endpoints
└── Frontend (Streamlit)
    ├── Image Upload & Camera Capture
    ├── Real-time Classification
    ├── Results Visualization
    └── Session State Management
🛠️ Technologies Used
Backend Technologies
Python 3.8+ - Core programming language

Flask - Web framework for API development

TensorFlow/Keras - Deep learning framework

MobileNetV2 - Pre-trained CNN model for image classification

Pillow (PIL) - Image processing library

Flask-CORS - Cross-origin resource sharing

NumPy - Numerical computations

Frontend Technologies
Streamlit - Rapid web application development

Pillow (PIL) - Image handling

Requests - HTTP client for API communication

Custom CSS - Professional styling and animations

AI/ML Components
Transfer Learning - Leveraging pre-trained MobileNetV2

Image Preprocessing - Resizing, normalization, encoding

Multi-class Classification - 3-category waste classification

Confidence Scoring - Probability-based predictions

🚀 Installation & Execution
Prerequisites
Python 3.8 or higher

pip package manager

Step 1: Clone the Repository
bash
git clone https://github.com/yourusername/waste-classification-ai.git
cd waste-classification-ai
Step 2: Install Dependencies
bash
pip install tensorflow flask flask-cors streamlit pillow requests
Step 3: Run the Backend Server
bash
python sample.py
Expected Output:

text
🔄 Loading MobileNetV2 model...
✅ Model loaded successfully!
🚀 Starting 3-Category Waste Classification Backend...
📡 Server running on: http://127.0.0.1:5000
Step 4: Run the Frontend Application
Open a new terminal and run:

bash
streamlit run app.py
Expected Output:

text
You can now view your Streamlit app in your browser.
Local URL: http://localhost:8501
Step 5: Access the Application
Open your browser and go to http://localhost:8501

Test the backend connection using the "Test Backend Connection" button

Upload an image or use camera capture

Click "CLASSIFY WASTE" to get predictions

📁 Project Structure
text
waste-classification-ai/
│
├── sample.py                 # Flask backend with AI model
├── app.py                    # Streamlit frontend application
├── requirements.txt          # Python dependencies
├── README.md                 # Project documentation
└── images/                   # Screenshots and demo images
    ├── demo1.png
    ├── demo2.png
    └── architecture.png
🔌 API Endpoints
Backend API (sample.py)
GET / - Home endpoint with API information

GET /health - Health check and model status

POST /predict - Main classification endpoint

GET /test - Simple test endpoint
