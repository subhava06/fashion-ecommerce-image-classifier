# 👗 Fashion MNIST Image Classifier

A complete end-to-end project to classify fashion images (like shirts, shoes, bags, etc.) using a **Convolutional Neural Network (CNN)** trained on the [Fashion-MNIST dataset](https://github.com/zalandoresearch/fashion-mnist).  
The project is wrapped in a **Streamlit web application** and fully containerized with **Docker**.

<br>

---

## 🚀 Project Flow

1. **Image Data** → Loaded from TensorFlow's built-in Fashion-MNIST dataset.  
2. **Data Preprocessing** → Normalization & reshaping of grayscale images.  
3. **Train-Test Split** → Automatic from dataset.  
4. **CNN Training** → Deep learning model built with TensorFlow/Keras.  
5. **Model Evaluation** → Accuracy and loss metrics.  
6. **Streamlit Web App** → Upload an image and get prediction.  
7. **Dockerfile** → Containerization setup.  
8. **Docker Image & Container** → Portable deployment.

<br>

---

## 🧩 Tech Stack

- **Python 3.10+**  
- **TensorFlow / Keras**  
- **NumPy & Pillow**  
- **Streamlit**  
- **Docker**  
<br>

---
## 📂 Project Structure

fashion-mnist-end-to-end/ <br>
│
├── app/ <br>
│ ├── main.py # Streamlit app <br>
│ ├── trained_model/ # Saved CNN model (.h5) <br>
│ ├── config.toml # Streamlit config <br>
│ ├── credentials.toml # Streamlit credentials <br>
│ ├── requirements.txt # Project dependencies <br>
│ └── Dockerfile # Docker build instructions <br>
│
├── notebooks/ # (Optional) Training notebooks <br>
└── README.md # Project documentation <br>


<br>

---

## 🖥️ Running the App Locally

### 1. Clone this repository
```bash
git clone https://github.com/<your-username>/fashion-ecommerce-image-classifier.git
cd fashion-ecommerce-image-classifier/app

2. Set up environment
python -m venv venv
venv\Scripts\activate   # On Windows
source venv/bin/activate  # On Mac/Linux

3. Install dependencies
pip install -r requirements.txt

4. Run the stramlit app
streamlit run main.py

```

---
<br>

## 🐳 Running with Docker


```bash
1. Build the image

docker build -t fashion-mnist-classifier-app .

<br>
2. Run the container

 docker run -p 8501:80 fashion-mnist-classifier-app

<br>
3. Open in browser

http://localhost:8501
```
<br>

---

## 📊 Results

Model trained on 60,000 training samples and evaluated on 10,000 test samples.

Achieved ~90% accuracy.

Predicts 10 fashion categories:

T-shirt/top, Trouser, Pullover, Dress, Coat, Sandal, Shirt, Sneaker, Bag, Ankle boot.

<br>

--- 

## 📸 Screenshots
<div align="center" style="display: flex; justify-content: space-around; font-size: 18px;">
  <span>🔹 Training Notebook</span>
  <span>🔹 Streamlit App</span>
  <span>🔹 Docker Run</span>
</div>

<p align="center"> 
 <img src="https://github.com/subhava06/fashion-ecommerce-image-classifier/blob/90991d78a0f0b9b07b9d59b06a4c6943ce527d4b/Screenshot%202025-09-15%20195334.png?raw=true" width="30%" style="margin: 10px;" /> 
 <img src="https://github.com/subhava06/fashion-ecommerce-image-classifier/blob/90991d78a0f0b9b07b9d59b06a4c6943ce527d4b/Screenshot%202025-09-15%20064448.png?raw=true" width="30%" height="10%" style="margin: 10px;" /> 
 <img src="https://github.com/subhava06/fashion-ecommerce-image-classifier/blob/90991d78a0f0b9b07b9d59b06a4c6943ce527d4b/Screenshot%202025-09-15%20195711.png?raw=true" width="30%" style="margin: 10px;" /> </p>


<br>

---

## 🔮 Future Improvements

Improve CNN architecture for higher accuracy.

Add support for batch image uploads.

Deploy on cloud (AWS/GCP/Heroku).

<br>

---

## 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss.

<br>
## 📜 License

This project is licensed under the MIT License.
`











