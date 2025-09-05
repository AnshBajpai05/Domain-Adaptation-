# Domain-Adaptation-
This project explores unsupervised domain adaptation for visual recognition using MNIST, MNIST-M, and Office-31. Implemented SVM, Random Forest, KNN, Logistic Regression, Naïve Bayes, XGBoost, AdaBoost, Stacking, PCA, MMD, CORAL, and CNN to reduce domain shift, improve transferability, and boost accuracy across domains.



## 🔍 Features
- Implemented a range of **classical ML models**:
  - SVM, KNN, Logistic Regression, Decision Trees, Naïve Bayes, Random Forest  
- Applied **ensemble methods**:
  - XGBoost, AdaBoost, Stacking Classifier  
- Built **deep learning approaches**:
  - **Lightweight CNN with SVM hinge loss** for better class separation and margin-based learning  
  - Domain Adversarial Neural Networks (DANN) for domain-invariant features  
- Used **discrepancy-based techniques**:
  - PCA (dimensionality reduction)  
  - MMD (Maximum Mean Discrepancy)  
  - CORAL (Correlation Alignment)  
- Explored **feature selection** to improve model interpretability and accuracy  

---

## 📂 Datasets
- **MNIST** – Grayscale handwritten digits  
- **MNIST-M** – Digits blended with colored backgrounds  
- **Office-31** – Images across Amazon, DSLR, and Webcam domains  

---

## 🚀 Results
- Baselines with SVM, Random Forest, and Stacking achieved ~90% accuracy  
- Discrepancy-based methods (MMD, CORAL) improved cross-domain transferability  
- **Lightweight CNN + hinge loss** enhanced generalization with fewer parameters  
- DANN achieved robust domain-invariant representations  
- Feature selection further boosted accuracy by focusing on key transferable features  

---

## 📌 Applications
- Cross-domain image recognition  
- Robust ML in real-world settings with domain shift  
- Foundation for **multi-loss and hybrid domain adaptation networks**  

---

## 🛠️ Tech Stack
- Python • NumPy • Pandas • Scikit-learn • PyTorch • Matplotlib  

---

## 📖 References
- "Domain-Adversarial Training of Neural Networks" (Ganin et al.)  
- "CORAL: Correlation Alignment for Deep Domain Adaptation" (Sun et al.)  
- "Maximum Mean Discrepancy for Domain Adaptation"  
- "Large Margin Deep Networks for Classification" (SVM hinge loss in deep models)  
