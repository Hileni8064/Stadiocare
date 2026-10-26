# CAP182 SS3 - Part B

## 📌 Overview
This notebook (`SS3_PartB.ipynb`) applies the final Random Forest method chosen in SS2 to the STADIOcare dataset.  
The workflow includes dataset loading, preprocessing, model training, validation, and results visualisation.

---

## 🗂 Dataset Loading
- Instances: 12,450
- Features: 18
- Target classes: Positive (30%), Negative (70%)
- Moderate class imbalance observed.

---

## 🔧 Dataset Preprocessing
- Standardization applied using `StandardScaler`.
- Stratified train/validation/test split (70/15/15).
- Ensures balanced evaluation and prevents bias.

---

## 🏗 Model Training
- Model: Random Forest Classifier
- Hyperparameters: n_estimators=200, max_depth=12
- Justification: Robust to imbalance, interpretable, prevents overfitting.
https://drive.google.com/file/d/1Zc5IQrMvo4nfkXyiqcPaM32dCEdGKg3G/view?usp=drive_link
---

## 📊 Model Validation
- Accuracy: 0.87
- Precision (Positive): 0.81 | Recall (Positive): 0.78 | F1: 0.79
- Precision (Negative): 0.90 | Recall (Negative): 0.92 | F1: 0.91
- Balanced performance across classes.

---

## 📈 Results Visualisation
- Confusion matrix heatmap included.
- Shows strong classification of Negative cases, with minor misclassifications in Positive cases.

---

## 💻 Technical Notes
- Notebook name: `SS3_PartB.ipynb`
- Commit history: Minimum of 5 commits (one per component).
- Repository includes:
  - Notebook
  - README.md
  - Dataset (`/data/` folder)
 
## Link to the video
https://drive.google.com/file/d/1Zc5IQrMvo4nfkXyiqcPaM32dCEdGKg3G/view?usp=drive_link

---

## 📌 Submission
File naming convention followed: `FirstNameLastName_StudentNumber_CAP182_SS3_PartB.ipynb`.  
Repository pushed to GitHub with correct commit history.

