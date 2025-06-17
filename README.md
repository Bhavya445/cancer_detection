

````markdown
# 🧠 Quantum vs Classical Classifier: Breast Cancer Detection

A hybrid quantum-classical machine learning mini-project that compares a **Classical SVM**, a **Quantum Kernel SVM**, and a **Quantum Neural Network (QNN)** for binary classification on the Breast Cancer Wisconsin dataset.

This project showcases hands-on knowledge in **quantum machine learning (QML)** using **PennyLane**, **PyTorch**, and **scikit-learn**.

---

## 📌 Project Structure

| Section                      | Description                                                                          |
|-----------------------------|--------------------------------------------------------------------------------------|
| `01_data_preprocessing`     | Load, normalize, and reduce breast cancer features to 4D for quantum embedding       |
| `02_classical_svm`          | Train and evaluate a classical SVM model                                             |
| `03_quantum_kernel_method`  | Use a quantum kernel with classical SVM for tagging                                  |
| `04_qnn_variational_model`  | Build a QNN using `qml.qnn.TorchLayer` and train it with PyTorch                     |
| `05_evaluation_comparison`  | Compare models using accuracy and confusion matrices                                 |

---

## 🔧 Technologies Used

- [PennyLane](https://pennylane.ai/)
- [PyTorch](https://pytorch.org/)
- [scikit-learn](https://scikit-learn.org/)
- Google Colab

---

## 📊 Results & Analysis

| Model                  | Accuracy   |
|------------------------|------------|
| Classical SVM          | 92.11%     |
| Quantum Kernel SVM     | 100.00%    |
| Quantum Neural Network | 60.00%     |

### 🧠 Interpretation

- **Classical SVM** performed well with high generalization, confirming its reliability on small to mid-sized datasets.
- **Quantum Kernel SVM** achieved perfect accuracy — this is likely due to overfitting on a **very small subset** (e.g., 20–30 samples), which is common in quantum simulations.
- **QNN (Variational Classifier)** showed lower accuracy, around 60%. This may be due to:
  - Limited training size (only ~100 samples),
  - Noisy gradients or poor convergence,
  - The difficulty of training parameterized quantum circuits on simulators.

> These results demonstrate the **potential** of quantum models, but also highlight **practical challenges** in training QML models on simulators with limited data and compute.

---

## 🚀 How to Run

Run the full notebook on [Google Colab](https://colab.research.google.com/):

```bash
# Optional: Clone locally
git clone https://github.com/Bhavya445/cancer_detection.git

# Install dependencies
pip install -r requirements.txt
````

---

## 📁 Files

* `cancer_detection.ipynb`: Main notebook with all models and comparisons
* `requirements.txt`: Dependency list for running locally
* `README.md`: Project overview

---

## 🎯 Goals

* Explore quantum ML through a practical classification task
* Compare classical and quantum methods head-to-head


---

## 👤 Author

**Bhavya Sunkari**
B.Tech @ IIT Mandi
Materials Science & Engineering + CS Minor
Quantum & AI enthusiast
[GitHub](https://github.com/Bhavya445)

---

## 📬 Contact

If you found this project useful or have feedback, feel free to star the repo or fork it.

```

---

```
