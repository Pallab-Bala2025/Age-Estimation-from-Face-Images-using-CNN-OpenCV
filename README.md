# Age-Estimation-from-Face-Images-using-CNN-OpenCV


# 📊 Age Estimation from Face Images using CNN & OpenCV

This project builds a deep learning pipeline to predict age ranges from face images.  
It combines **OpenCV** for face detection and preprocessing, with a **Convolutional Neural Network (CNN)** built using **TensorFlow/Keras** to classify images into age groups.

---

## 🚀 Features
✅ Face detection using OpenCV Haar cascades to extract face regions from images.  
✅ Preprocessing pipeline to resize, normalize, and prepare face images for training.  
✅ Trains a CNN to classify age into predefined ranges (age groups).  
✅ Predicts age range on new test images.  
✅ Visualization of predictions vs actual images.

---

## 📂 Dataset
This implementation uses a **custom dataset** organized in folders representing different age ranges.  
Each folder contains images corresponding to that age range.

Example structure:

dataset/
├── (0-2)/
├── (4-6)/
├── (8-13)/
├── (15-20)/
├── (25-32)/
├── (38-43)/
├── (48-53)/
└── (60-100)/

✅ Dataset images are processed to extract face regions using OpenCV before feeding into the model.

---

## 🛠 Tech Stack
- **Python**
- **TensorFlow / Keras**
- **OpenCV**
- **NumPy, Matplotlib**

---

## 📈 Results
- Trained a CNN model on the dataset images classified by age ranges.
- The model predicts the most probable age range of new face images.

---

## 🚀 How to Run
1. **Clone the repository**
    ```
    git clone https://github.com/Pallab-Bala2025/Age-Estimation-from-Face-Images-using-CNN-OpenCV.git
    cd Age-Estimation-from-Face-Images-using-CNN-OpenCV
    ```

2. **Run the notebook**
    - Open `Age_Detection_.ipynb` in Google Colab or Jupyter Notebook.
    - Execute the cells step by step to:
      - Load and preprocess data
      - Train the CNN model
      - Test predictions on sample images

---

## 🖼️ Sample Predictions
| Input Face | Predicted Age Range |
|------------|---------------------|
| ![Sample1](samples/sample1.jpg) | (15-20) |
| ![Sample2](samples/sample2.jpg) | (25-32) |

---

## ✅ Future Improvements
- Use pre-trained models (e.g. MobileNet, VGGFace) for better feature extraction.
- Implement regression to predict exact age instead of age groups.
- Train on larger datasets like [Adience](https://talhassner.github.io/home/projects/Adience/Adience-data.html).

---

## 👤 Author
- **Pallab Bala**  
- [GitHub](https://github.com/Pallab-Bala2025)

---

## 📜 License
This project is open-sourced for educational purposes.

---

