

Project Overview

This repository contains my from-scratch implementation of:

* Linear Regression (for continuous prediction)
* Logistic Regression (for binary classification)

Both models are implemented using only **NumPy**, without using Scikit-learn, to deeply understand the mathematical foundations behind Machine Learning algorithms.

The goal of this project was to build strong intuition around:

* Gradient Descent
* Loss functions
* Optimization behavior
* Decision boundaries
* Effect of learning rate
* Weight and bias interpretation

---

Linear Regression

### Concepts Implemented

* Hypothesis function:
  ( y = wx + b )

* Mean Squared Error (MSE) loss

* Gradient Descent optimization

* Learning rate experimentation:

  * Small learning rate → slow convergence
  * Large learning rate → divergence / unstable updates
  * Proper learning rate → smooth loss curve

* Visualization of:

  * Loss vs Epochs
  * Effect of different learning rates

### Key Learnings

* Why loss decreases gradually
* Why it never becomes exactly zero in real cases
* How gradient descent updates weights
* Why feature scaling matters
* How optimization behaves mathematically

---

 Logistic Regression

### Concepts Implemented

* Linear combination:
  ( z = wx + b )

* Sigmoid activation function

* Binary Cross Entropy (Log Loss)

* Decision boundary:
  ( wx + b = 0 )

* Multi-feature logistic regression using vectorization:
  ( z = W^T X + b )

* Gradient derivation in matrix form

### Key Learnings

* Why sigmoid is required for classification
* Why MSE is not suitable for classification
* How cross-entropy punishes confident wrong predictions
* How weight controls slope (confidence sharpness)
* How bias shifts decision boundary
* Understanding linear separability

---

# 🛠️ Tech Stack

* Python
* NumPy
* Matplotlib

(No ML libraries used for model implementation)

---

# 📊 What This Project Demonstrates

* Strong understanding of ML fundamentals
* Ability to derive gradients manually
* Clear understanding of optimization
* Mathematical intuition behind classification
* Comfort with vectorized numerical computation
* Engineering mindset (not just library usage)

---

# 🚀 Next Steps

Planned improvements:

* Add feature scaling (standardization)
* Add regularization (L1/L2)
* Compare with Scikit-learn implementation
* Extend to multi-class classification
* Build end-to-end ML pipeline
* Deploy model using FastAPI or Streamlit

---

# 🎯 Why This Matters

Understanding ML from scratch builds strong foundations required for:

* Machine Learning Engineering
* Deep Learning
* Applied AI
* Production ML systems

This project focuses on understanding the “why” behind algorithms, not just the “how”.
