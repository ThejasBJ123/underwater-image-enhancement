
# 🌊 Underwater Image Enhancement Using Deep Learning

This project enhances underwater images using deep learning techniques to restore clarity, color, and detail. Designed as part of the CS517 curriculum, it addresses the visibility and distortion challenges in underwater photography, crucial for marine biology, diving, and surveillance.

## 🔍 Project Overview

Underwater images often suffer from:
- Color distortion due to light absorption
- Hazy appearance from scattering
- Loss of detail and contrast

We propose an image enhancement system using deep neural networks to restore visual quality in a fully automated pipeline.

## 🧠 Key Features

- 📦 Trained on raw/reference image pairs
- 🧪 Evaluates enhancement quality using image metrics
- 🌐 Simple web interface using `Flask`
- ☁️ Deployable via Heroku with `Procfile` and `setup.sh`

## 📂 Folder Structure

```
underwater-image-enhancement-main/
│
├── Project.ipynb            # Main deep learning notebook
├── uie_web_app.py           # Web app using Flask
├── requirements.txt         # Python dependencies
├── dataset/
│   ├── raw/                 # Input underwater images
│   └── reference/           # Ground truth for comparison
├── CS517 Project Report.pdf
└── README.md
```

## 🚀 How to Run This Project

### Option 1: Run Locally

```bash
# Clone the repository (or extract ZIP contents)
cd underwater-image-enhancement-main

# Create a virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run the web application
python uie_web_app.py
```

Then visit `http://127.0.0.1:5000/` in your browser to use the image enhancement tool.

---

### Option 2: Run via Jupyter Notebook

```bash
# Open the notebook
jupyter notebook Project.ipynb
```

This allows you to experiment with the enhancement pipeline step-by-step.

## 💡 Technologies Used

- Python
- OpenCV, NumPy
- TensorFlow/Keras or PyTorch (depending on notebook)
- Flask for web deployment

## 🎓 Academic Contribution

This project was developed as part of the **CS517 - Advanced Image Processing** course. It explores real-world applications of deep learning in image restoration and quality enhancement.

---

## 📸 Sample Results

| Input Image | Enhanced Output |
|-------------|------------------|
| ![](dataset/raw/Img1.png) | ![](dataset/reference/RImg1.png) |

---

## 📬 Contact

Feel free to connect or reach out on [LinkedIn](https://www.linkedin.com/) and contribute to the project!

