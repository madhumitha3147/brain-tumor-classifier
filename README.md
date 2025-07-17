# 🧠 Brain Tumor MRI Classification using CNN & VGG16

This project aims to classify brain tumors using deep learning techniques on MRI images. Built as part of a minor project for **Artificial Intelligence with Python**, it demonstrates image preprocessing, model building with **Vanilla CNN** and **VGG16 (transfer learning)**, and performance evaluation on real-world MRI data.

---

## 📁 Dataset

- Source: [Kaggle - Brain Tumor MRI Dataset](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset)
- Contains MRI scans categorized into:
  - `glioma`
  - `meningioma`
  - `pituitary`
  - `no tumor`

---

## 🚀 Models Used

### ✅ Vanilla CNN
- Custom convolutional neural network with grayscale images
- Achieved decent accuracy with limited layers

### ✅ VGG16 Transfer Learning
- Used pre-trained VGG16 base from ImageNet
- Trained with RGB MRI images
- Achieved **~88% validation accuracy**

---

## 📊 Results

- **Train Accuracy**: ~82%
- **Validation Accuracy**: ~88%
- Plotted **Accuracy vs Epochs** and **Loss vs Epochs**
- Evaluated with:
  - Classification Report
  - F1 Score, Precision, Recall
- Single image prediction with **bar chart probability visualization**

---

## 🧪 Sample Prediction Output

![Sample prediction](path-to-your-bar-chart.png)

---

## 🛠️ Technologies Used

- Python
- Google Colab
- OpenCV
- TensorFlow / Keras
- NumPy, Matplotlib, Sklearn

---

## 📌 How to Run

1. Download the dataset from Kaggle
2. Upload to Colab or run locally
3. Run the notebook cells step-by-step
4. Optionally export your own model or visualize predictions

---

## 👤 Author

**Your Name Here**  
AI Minor Project | Artificial Intelligence with Python  
GitHub: [@madhumitha3147](https://github.com/madhumitha3147)




