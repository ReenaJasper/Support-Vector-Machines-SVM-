SVM Classification on Breast Cancer Dataset

What We Did
- Loaded & normalized breast cancer data
- Trained SVM with both **linear** and **RBF** kernels
- Evaluated models using accuracy & confusion matrix
- Tuned `C` and `gamma` using `GridSearchCV`
- Performed 5-fold cross-validation

Accuracy
- Linear SVM: 0.97 (example)
- RBF SVM: 0.98 (example)
- Best parameters: `{'C': 1, 'gamma': 'scale', 'kernel': 'rbf'}`

Concepts Covered
- Margin maximization
- Kernel trick
- Hyperparameter tuning
- Cross-validation

Libraries
- scikit-learn
- matplotlib
- seaborn
- pandas, numpy
