# Digit Classifier API

A deep learning-based REST API that recognizes handwritten digits (0-9), built with TensorFlow/Keras and deployed on the cloud using Flask.

## 🔗 Live Demo
[https://digit-classifier-api-xxxx.onrender.com](https://digit-classifier-api-xxxx.onrender.com)

## 🛠️ Tech Stack
- **Python** — core programming language
- **TensorFlow / Keras** — model training (Neural Network)
- **Flask** — REST API framework
- **Render** — cloud deployment
- **Dataset:** MNIST (handwritten digits)

## 📊 Model Performance
- Test Accuracy: **97.67%**
- Architecture: Dense Neural Network (128 → 64 → 10 layers)

## 🚀 How It Works
1. Client sends an image of a handwritten digit to the `/predict` endpoint
2. The image is preprocessed (resized to 28x28, normalized)
3. The trained model predicts the digit and returns the result as JSON

## 📡 API Usage
**Endpoint:** `POST /predict`

**Request:** Send an image file with key `image`

**Response:**
```json
{
  "predicted_digit": 7,
  "confidence": 0.987
}
```

## 💻 Run Locally
```bash
pip install -r requirements.txt
python ronic_app.py
```

## 👤 Author
**Ronic Vasane**
