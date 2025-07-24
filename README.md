# 🧠 Brain Tumor Classification using MRI Images

This deep learning project detects brain tumors from MRI images using Convolutional Neural Networks (CNN) and Transfer Learning (VGG16).  
The model classifies brain scans into 4 categories: **Glioma**, **Meningioma**, **Pituitary Tumor**, and **No Tumor**.

---

## 📂 Dataset

📎 **Source:** [Labeled MRI Brain Tumor Dataset – Roboflow v1](https://universe.roboflow.com/ali-rostami/labeled-mri-brain-tumor-dataset)  
📜 **License:** CC BY 4.0

### 📊 Dataset Details:

| Category           | Count   |
|--------------------|---------|
| Total Images       | 2443    |
| Training Set       | 1695    |
| Validation Set     | 502     |
| Test Set           | 246     |
| Image Type         | MRI Scans |
| Labeled Classes    | Glioma, Meningioma, Pituitary, No Tumor |

Labeled by medical experts using standardized labeling protocols.

---

## 🧪 Models Trained

### ✅ ML Model 1 – CNN (from scratch)
- Accuracy: 93.2%
- F1 Score: 91.8%

### ✅ ML Model 2 – VGG16 Transfer Learning (Final Model)
- Accuracy: 96.7%
- F1 Score: 95.2%
- Explainable using Grad-CAM

### ✅ ML Model 3 – CNN (Tuned)
- Accuracy: 94.5% after hyperparameter tuning

---

## 🔍 Evaluation Metrics

- **Accuracy**
- **Precision**
- **Recall (Sensitivity)**
- **F1 Score**
- **Confusion Matrix**
- **Grad-CAM Visualizations** for model transparency

---

## 🚀 How to Run the Project

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/brain-tumor-classification.git
cd brain-tumor-classification
