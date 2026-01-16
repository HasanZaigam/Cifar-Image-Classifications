# Multi-Level Image Classification Challenge — CIFAR-10  
**Candidate:** Hasan Zaigam  
**Role Target:** AI + Backend (ML Engineer)  
**Submission Date:** 16 Jan 2026  

---

## 🚀 Problem Overview  
This project is submitted for the TeraFac hiring challenge.  
The objective was to build and evaluate a multi-level image classification system on the CIFAR-10 dataset (10 object classes, 60k images).

---

## 📦 Dataset: CIFAR-10  
- Train: 80%
- Validation: 10%
- Test: 10%
- Classes: airplane, automobile, bird, cat, deer, dog, frog, horse, ship, truck

Dataset was loaded using PyTorch's built-in API.

---

## 🧩 Levels Completed  
| Level | Description | Status |
|-------|-------------|--------|
| Level 1 | Baseline transfer learning model | ✅ Completed |
| Level 2 | Augmentation + Regularization improvements | ✅ Completed |
| Level 3 | Custom Architecture + GradCAM analysis | ✅ Completed |
| Level 4 | Ensemble Learning | ✅ Completed |
| Level 5 | Optional Production System | ✅ Completed  |

---

## 🔗 Google Colab Notebook  
Full runnable code with visible outputs:  
👉 **Colab Link:** <PASTE YOUR COLAB LINK HERE>

Notebook file is also included in this repo:  
`Terefac_hasan_zaigam.ipynb`

---

## 🛠 Tech Stack  
- PyTorch
- Torchvision
- Timm (Transfer Models)
- NumPy
- Matplotlib
- Grad-CAM
- FastAPI (optional backend)
- Google Colab GPU Runtime

---

## 🧪 Experiments Summary  

### 📍 Level 1: Baseline Model  
Model: ResNet50 (transfer learning)  
Accuracy Achieved: **XX%**  

### 📍 Level 2: Improvements  
Techniques applied:
- Data Augmentation
- Learning Rate Scheduling
- Weight Decay
- BatchNorm

Accuracy Improved: **XX% → XX%**

### 📍 Level 3: Custom Model & Explainability  
- Custom CNN Model
- Grad-CAM visualization for interpretability
Shows visual attention regions for classification decisions.

### 📍 Level 4: Ensemble Model  
Models used:
- ResNet50  
- EfficientNet-B0  
- ViT Tiny  

Ensemble Strategy: Softmax Averaging  

Final Ensemble Accuracy: **XX%**

---

## 📁 Project Structure  
```
📦 cifar-image-classification
 ├── Terefac_hasan_zaigam.ipynb
 ├── requirements.txt
 ├── README.md
 └── report.pdf (Terefac_Hasan-Zaigam (1))
```

---

## 📊 Results & Screenshots  
Visual outputs are included in the PDF and results folder:
- Training curves
- Validation curves
- Confusion matrix
- Sample predictions
- Grad-CAM heatmaps

---

## 🔧 Installation & Running Instructions  
```
pip install -r requirements.txt
```

For notebook:
```
Run on Google Colab (GPU recommended)
```

---

## 📜 Requirements  
```
torch
torchvision
timm
numpy
matplotlib
opencv-python
scikit-learn
grad-cam
```

---

## 📑 Conclusion  

Key Observations:
- Transfer learning significantly boosts performance
- Data augmentation solves overfitting
- Ensemble improves final score further
- Model interpretable with Grad-CAM

Future Work:
- Production-ready FastAPI serving
- Quantization + Deployment
- Distillation for edge inference

---

## 📣 Credits  
Challenge organized by: **TeraFac**  
Executed by: **Hasan Zaigam**
