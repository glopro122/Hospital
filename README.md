# Algorithmic Complexity & Empirical Benchmarking Suite

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![NumPy](https://img.shields.io/badge/NumPy-Data-blue?logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebooks-orange?logo=jupyter)

A computational benchmarking and asymptotic complexity analysis suite developed in Python. This project evaluates searching, sorting, and matrix operations empirically against their theoretical mathematical runtime bounds: $\Theta(1)$, $\Theta(n)$, $\Theta(\log n)$, $\Theta(n^2)$, and $\Theta(n^3)$.

---

## 📌 Key Objectives & Architecture

1. **Empirical Runtime Benchmarking:** High-resolution runtime measurement across variable input sizes ($n$).
2. **Mathematical Asymptotic Verification:** Fitting empirical execution times into formal complexity functions by calculating empirical normalization constants ($c$):
   $$T(n) = c \cdot f(n)$$
   * Linear Search: $T = 5.63 \times 10^{-8} \cdot n$
   * Binary Search: $T = 5.02 \times 10^{-7} \cdot \log_2(n)$
   * Bubble Sort: $T = 1.76 \times 10^{-7} \cdot n^2$
   * Matrix Multiplication: $T = 2.07 \times 10^{-7} \cdot n^3$
3. **Data Visualization:** Comparative plots contrasting real-world wall-clock execution against theoretical Big-O curves using `matplotlib`.

---

## 📂 Repository Contents

* `Final.ipynb`: Complete algorithmic benchmark notebook containing best, worst, and average-case analysis with theoretical derivations and charts.
* `graficas.ipynb`: Execution time plots and asymptotic curve fitting scripts.
* `tabla*.ipynb`: Tabular benchmark datasets and performance summaries.

---

## 🚀 How to Run Locally

### 1. Prerequisites
Ensure you have Python 3.9+ and pip installed.

### 2. Clone the repository
```bash
git clone https://github.com/glopro122/Hospital.git
cd Hospital
```

### 3. Install dependencies
```bash
pip install numpy matplotlib pandas jupyter
```

### 4. Launch Jupyter Notebook
```bash
jupyter notebook Final.ipynb
```

---

## 👨‍💻 Authors
Developed by **Manuel González** and collaborators as part of the Algorithms and Data Structures curriculum at **Universidad del Norte (Uninorte)**.
