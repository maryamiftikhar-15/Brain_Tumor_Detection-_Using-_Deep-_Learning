# 🧠 Brain Tumor Detection using Deep Learning

This project detects brain tumors from MRI scans using deep learning techniques. It compares multiple models to evaluate performance, including:

- Custom CNN  
- VGG16 (transfer learning)  
- ResNet50 (transfer learning)  
- EfficientNetB0 (transfer learning)  

The project explores the effect of dataset quality on performance and shows how model accuracy improves with better data.

## 📁 Folder Structure

- `notebooks/`: Jupyter notebooks for all experiments  
- `models/`: Saved trained models  
- `results/`: Accuracy/loss plots, confusion matrices, classification reports  

> Due to size limitations, **models and result plots are stored externally**:  
🔗 [View models and results on Google Drive](https://drive.google.com/drive/folders/1JGRP9bTDea3a9cCqUn5FvgnJo9QOeqK8?usp=sharing)

## 📊 Approximate Model Performance

| Model             | Accuracy |
|------------------|----------|
| CNN (Initial)     | ~76%     |
| CNN (Improved)    | ~88%     |
| VGG16             | ~90%     |
| ResNet50          | ~96%     |
| EfficientNetB0    | ~93%     |

---

### ✅ How to Run

1. Clone the repository  
2. Open any notebook in `notebooks/`  
3. Run the cells to train/evaluate models
