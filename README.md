# 🧠 Image Classification Using Convolutional Neural Networks (CNN)
# 🧠 NEURAL-ART: Ghibli Style Transfer App 🎨  
### ✨ Turn Your Photos into Magical Studio Ghibli Art

Transform everyday images into stunning, stylized masterpieces using **Neural Style Transfer (NST)** powered by **Convolutional Neural Networks (CNNs)**. This web-based project uses **VGG19** to blend the **content of a real photo** with the **style of a Ghibli-style artwork** – a perfect fit for artists, designers, and anime enthusiasts.

---

## 🖼️ Sample Results

| 📷 Content Image | 🖌️ Style Image | 🎨 Stylized Output |
|------------------|----------------|---------------------|
| ![](images/content_sample.jpg) | ![](images/style_sample.jpg) | ![](images/output_sample.jpg) |


## 🧰 Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Git & GitHub

---

## 🚀 Features

- Pre## 🚀 Features

- 📂 Upload content & style images via UI
- 🧠 Uses VGG19 for content & style extraction
- ⚙️ Optimization via Adam and gradient descent
- 💾 Saves output image locally
- 🌐 Flask-based interactive web app

## 🔍 How It Works

1. Upload a **content image** (your photo)
2. Upload a **style image** (Ghibli frame or painting)
3. The app fuses them using:
   - **Content Loss** from deep layers
   - **Style Loss** using **Gram Matrices**
4. The output is saved and previewed in your browser.

## 🛠️ Installation

### Prerequisites
Make sure Python and pip are installed. Then install the required libraries:

```bash
pip install tensorflow numpy matplotlib
