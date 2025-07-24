# 🧠 Brain Tumor Classification using MRI Images

This deep learning project detects brain tumors from MRI images using Convolutional Neural Networks (CNN) and Transfer Learning (VGG16).  
The model classifies brain scans into 4 categories: **Glioma**, **Meningioma**, **Pituitary Tumor**, and **No Tumor**.

---

## 📂 Dataset

📎 **Source:** [Labeled MRI Brain Tumor Dataset – Roboflow v1](https://universe.roboflow.com/ali-rostami/labeled-mri-brain-tumor-dataset)  
📜 **License:** CC BY 4.0

You can download the dataset from the link below:

🔗 **[Download Dataset from OneDrive](https://1drv.ms/u/s!Your-Link-Here)**

> ⚠️ *Note: Due to GitHub file size limitations, the dataset is not included in this repository.*

---

## 📊 Dataset Details:

| Category           | Count   |
|--------------------|---------|
| Total Images       | 2443    |
| Training Set       | 1695    |
| Validation Set     | 502     |
| Test Set           | 246     |
| Image Type         | MRI Scans |
| Labeled Classes    | Glioma, Meningioma, Pituitary, No Tumor |

---

## 🧪 Models Trained

### ✅ ML Model 1 – CNN (from scratch)
- Accuracy: 93.2%
- F1 Score: 91.8%

### ✅ ML Model 2 – VGG16 Transfer Learning (**Best Model**)
- Accuracy: **96.7%**
- F1 Score: **95.2%**
- Explainable using Grad-CAM visualizations

### ✅ ML Model 3 – CNN + Hyperparameter Tuning
- Accuracy: 94.5%

---

## 🔍 Evaluation Metrics

- **Accuracy**
- **Precision**
- **Recall (Sensitivity)**
- **F1 Score**
- **Confusion Matrix**
- **Grad-CAM Visualizations** for transparency

---

## 🚀 How to Run the Project

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/brain-tumor-classification.git
cd brain-tumor-classification
