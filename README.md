# Visual Data Inspect AI

An AI-driven visual inspection system that uses Machine Learning and image texture analysis to automatically classify product quality based on visual data. This project applies feature engineering, statistical texture extraction, and multiple classical classifiers to automate visual quality assessment.

---

## 🚀 Overview
VisualDataInspect AI demonstrates how data-driven image processing techniques can power industrial visual inspection workflows.  
Using Haralick texture features extracted with Mahotas, the project evaluates multiple traditional ML classifiers, from Logistic Regression to Neural Networks to find the best-performing approach for automated defect detection.

---

## 🧠 Tech Stack
Python · NumPy · Pandas · scikit-learn · Mahotas · Matplotlib · Seaborn

---

## 📊 Key Features
- Converts raw RGB images into numerical texture features  
- Compares 10+ ML algorithms for image classification  
- Generates confusion matrices and accuracy visualizations  
- Automates training, validation, and test set evaluation  
- Saves classification outputs and predictions to CSV  

---

## 🧾 How to Run
Clone the repository, install dependencies, and execute the script:

```bash
git clone https://github.com/<your-username>/VisualDataInspect-AI.git
cd VisualDataInspect-AI
pip install -r requirements.txt
python VisualDataInspect_AI.py
```

Make sure your dataset folder and CSV files follow this structure:
```
/hiroshima-lemon/
 ├── train_images/
 ├── test_images/
 ├── train_images.csv
 └── test_images.csv
```

---

## 📈 Results
- Achieved strong classification accuracy across multiple ML algorithms  
- Logistic Regression, Gaussian Process, and Neural Net delivered best validation results  
- Demonstrated efficient, scalable image inspection workflow  

---

## 📄 License
Licensed under the MIT License — see the LICENSE file for details.
