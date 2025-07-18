# 🍈 Soursop Ripeness Classification using CNN

This project is based on my undergraduate thesis at Universitas Negeri Yogyakarta (UNY), which focuses on classifying the ripeness level of soursop (Annona muricata L) fruits — categorized as unripe, half-ripe, and ripe — using image processing and Convolutional Neural Network (CNN).

---

## 📌 Project Overview

- **Title**: Identification of Soursop Ripeness Based on Texture and Color Using CNN
- **Author**: Kharisma Nur’aisyah
- **University**: Universitas Negeri Yogyakarta
- **Degree**: Bachelor of Science in Mathematics
- **Year**: 2022

---

## 🎯 Objective

To create an image classification model that can automatically identify the ripeness level of soursop fruits from texture and color using CNN.

---

## 📸 Dataset

- 📍 Collected in Bantul, Yogyakarta, Indonesia
- 📷 Captured using OPPO A15s smartphone
- 📁 Format: JPG
- 🖼 Total Images: 595
  - Unripe: 205 images
  - Half-ripe: 125 images
  - Ripe: 265 images
- 🧪 Data split:
  - 80% training
  - 20% testing

---

## 🧠 Method

- Model: **Convolutional Neural Network (CNN)**
- Architecture: 3 convolutional layers + pooling + fully-connected layers
- Image Preprocessing: resizing, cropping, sharpening, augmentation
- Tools & Libraries:
  - Python
  - Google Colab
  - TensorFlow / Keras
  - OpenCV, NumPy, Matplotlib

---

## 📊 Results

| Dataset       | Accuracy  |
|---------------|-----------|
| Training      | 85.50%    |
| Testing       | 83.19%    |
| New Images    | 73.33%    |

---

## 📂 Project Structure
soursop-ripeness-cnn/
├── README.md
├── soursop-ripeness-cnn.ipynb # Main notebook
├── thesis-soursop-cnn.pdf # Full thesis (in Bahasa Indonesia)
├── presentation-soursop-cnn.pdf # Final defense slides
└── data/
├── unripe.jpg
├── half-ripe.jpg
└── ripe.jpg

---

## 🚀 How to Run

This project was developed in **Google Colab**.  
To run it:

1. Open the `.ipynb` notebook in Google Colab
2. Upload the sample dataset (or use your own)
3. Run the notebook cells from top to bottom
4. The model will train and display accuracy, loss, and classification results

---

## 🎤 Presentation

The final defense presentation is available here:  
👉 [`presentation-soursop-cnn.pdf`](./presentation-soursop-cnn.pdf)

---

## 📜 License

This project is made available for educational and personal portfolio purposes. All data and materials were collected and created by the author.

---

## 🙏 Acknowledgements

Special thanks to:
- Dr. Sri Andayani, S.Si., M.Kom (Thesis Advisor)
- Mentors and friends from the BRI internship program
- All individuals who helped during data collection and model development
