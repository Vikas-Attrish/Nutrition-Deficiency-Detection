🌱 **Nutrient Deficiency Detection in Rice Leaves**

## 📌 Project Overview
This project focuses on detecting **nutrient deficiencies (Nitrogen, Phosphorus, and Potassium)** in rice leaves using **image processing and machine learning techniques**. By analyzing rice leaf images, the system identifies early symptoms of nutrient stress, helping farmers take corrective actions to improve crop yield.

## 📂 Dataset
- Source: [Nutrient Deficiency Symptoms in Rice (Kaggle)](https://www.kaggle.com/)
- Classes: 
  - Healthy  
  - Nitrogen Deficient  
  - Phosphorus Deficient  
  - Potassium Deficient  

The dataset was stored in **Google Drive** and accessed in **Google Colab** for training.

## ⚙️ Methodology
1. **Image Preprocessing**  
   - Image segmentation (isolate leaf regions)  
   - Contrast stretching and enhancement  
   - Data augmentation (rotation, flipping, scaling)  

2. **Model Training**  
   - **CNN** (baseline and best performing so far)  
   - **ResNet50** (transfer learning)  
   - **Random Forest** (on extracted features)  
   - **SVM** (support vector machine)  
   - **LightGBM** (boosting classifier)  

3. **Evaluation Metrics**  
   - Accuracy  
   - Precision, Recall, F1-score  
   - Confusion Matrix  

## 📊 Results
- **CNN** achieved the **best accuracy** among tested models.  
- Random Forest, SVM, and LightGBM provided baseline comparisons.  
- Ongoing work: Hyperparameter tuning and deeper transfer learning (ResNet50) to further improve accuracy.  

## 🛠️ Tech Stack
- **Languages**: Python  
- **Libraries**: TensorFlow/Keras, OpenCV, NumPy, Pandas, Scikit-learn, LightGBM, Matplotlib, Seaborn  
- **Environment**: Google Colab (GPU enabled)  

## 📖 Reference
- *Identification of Nutrient Deficiency Based on Leaf Image Data Using Machine Learning* — Kavitha S, ESCI 2024.

---

## 🚀 How to Run
1. Clone this repository:  
   ```bash
   git clone https://github.com/Vikas-Attrish/Nutrition_Deficiency_Detection.git
   cd Nutrition_Deficiency_Detection
