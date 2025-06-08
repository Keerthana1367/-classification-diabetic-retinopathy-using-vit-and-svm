# -classification-diabetic-retinopathy-using-vit-and-svm
This project focuses on automated classification of Diabetic Retinopathy (DR) stages from retinal fundus images using a hybrid deep learning and machine learning approach. It combines the power of Vision Transformer (ViT) for feature extraction and Support Vector Machine (SVM) for robust classification.


This project focuses on automated classification of Diabetic Retinopathy (DR) stages from retinal fundus images using a hybrid model that combines **Vision Transformer (ViT)** for feature extraction and **Support Vector Machine (SVM)** for classification.

---

 Project Structure
- `DATASET/` – Contains sample retinal images used for training/testing.
- `Diabetic_Retinopathy.pdf` – Detailed report explaining methodology, results, and evaluation.
- `ML_diabetic_final.pptx` – Presentation slides summarizing the project.
- `README.md` – Project overview and usage instructions.

---

 Methodology
- Images are preprocessed and normalized.
- ViT is used to extract high-dimensional image features.
- Features are fed into an SVM classifier for final stage prediction.
- Classifies DR into:
  - No DR
  - Mild
  - Moderate
  - Severe
  - Proliferative DR

---
Tech Stack
- Python
- PyTorch
- scikit-learn
- OpenCV
- NumPy

---
 Results
- Achieved high classification accuracy with efficient feature extraction.
- Reduced training complexity compared to full deep learning models.
---

   References
- APTOS 2019 Blindness Detection Dataset (Kaggle)
- Vision Transformer by Google Research

---

 Future Work
- Deploy using a web interface for clinician use.

---

Acknowledgements
This project was completed as part of a Machine Learning academic module.

