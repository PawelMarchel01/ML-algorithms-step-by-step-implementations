# 🧮 ML Algorithms: Step-by-Step Implementations

Step-by-step implementation of core Machine Learning algorithms with performance comparisons against sklearn implementations.

---

##  1. **Linear Regression**  
   - 📉 Implemented both **analytical** and **numerical** solutions:  
     - Closed-form linear regression  
     - Powell’s optimization method (scipy)  
   - 🧪 Tested on synthetic 1D datasets (`make_regression`, noise=16)  
   - ⏱️ Compared in terms of **accuracy** and **runtime**

---

##  2. **Linear Classification**  
   - 🧾 Analytical implementation with **Tikhonov regularization**  
   - 🧪 Benchmarked against `RidgeClassifier` from sklearn  
   - ❤️ Applied to **Cleveland Heart Disease** dataset:
     - Data preprocessing, outlier removal  
     - Statistical profiling and feature selection (manual vs automatic)  

---

##  3. **Logistic Regression**
   - ⚙️ Custom implementation using:
     - **Gradient Descent** (with learning rate tuning)
     - ✨ **Mini-Batch** optimization
     - 📉 **Squared Gradients Sum** (AdaGrad-style)
   - 🧪 Tested on synthetic datasets:
     - Binary classification
     - Multi-class scenarios

---

##  4. **SVM (Support Vector Machines)**
   - 🔧 Three kernel implementations:
     - ➖ **Linear Kernel** (hard/soft margin)
     - 🔶 **Polynomial Kernel** (degree customization)
     - 🌐 **RBF Kernel** (gamma parameter tuning)
   - ⚖️ Benchmarking against sklearn's SVM:
     - Accuracy comparison
     - Training time analysis
   - 📊 Visualization of decision boundaries

---

##  5. **Decision Tree**
   - 🌡️ **Entropy Minimization** approach:
     - Recursive binary splitting
     - Pre-pruning parameters
   - 🧪 Test scenarios:
     - Single-feature datasets
     - High-dimensional multi-class problems
   - 📉 Comparison with sklearn's DecisionTreeClassifier

---

##  6. **Random Forest**
   - 🏗️ Custom ensemble features:
     - Bagging with replacement
     - Feature subspace selection
     - Comparison with sklearn.ensemble.RandomForest

---

##  7. **Neural Network (Custom Implementation)**  
   - 🧠 Manually built **multi-layer feedforward neural network**
   - 📦 Trained on **MNIST** with adjustable activation functions (e.g., ReLU, Sigmoid)  
   - 📈 Reports metrics after each epoch: **accuracy**, **sensitivity**, **specificity**  

---

## 👨‍💻 Author  
**Paweł Marchel**  
If you find this project helpful, feel free to star ⭐ the repo or get in touch for collaboration.
