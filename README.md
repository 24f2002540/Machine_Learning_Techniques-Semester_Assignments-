# Machine Learning Techniques – Semester Assignments
### IIT Madras | B.S. Data Science and Applications

This repository contains weekly programming assignments from the **Machine Learning Techniques** course offered by IIT Madras as part of the B.S. Data Science and Applications program. Each notebook covers a core ML concept, implemented from scratch using Python, NumPy, and Matplotlib.

---

## 📁 Repository Structure

| Notebook | Topic |
|---|---|
| `MLT_WEEK_1_Programming.ipynb` | Principal Component Analysis (PCA) |
| `MLT_WEEK_2_programming.ipynb` | Kernel Methods (Polynomial & RBF Kernels) |
| `MLT_WEEK_3_prog_assignment_ques.ipynb` | K-Means Clustering |
| `MLT_WEEK_4_part-1.ipynb` | Probabilistic Modelling & MLE (Bernoulli / Categorical) |
| `MLT_WEEK_4_part-2.ipynb` | Gaussian Mixture Models & EM Algorithm |
| `MLT_WEEK_5_Programming.ipynb` | Linear Regression & Kernel Regression |
| `MLT_WEEK_6_programming.ipynb` | Train-Test Split, Data Preprocessing & Regression Pipeline |
| `MLT_WEEK_7_programming.ipynb` | Decision Trees & K-Nearest Neighbours (KNN) |

---

## 🧠 Topics Covered

### Week 1 – Principal Component Analysis (PCA)
- Data centering and covariance matrix computation on the MNIST dataset
- Eigenvalue decomposition to extract principal components
- Dimensionality reduction and image visualization using Matplotlib

### Week 2 – Kernel Methods
- Computing Polynomial and Gaussian (RBF) kernel matrices from scratch
- Centering kernel matrices in feature space
- Applied on a synthetic `make_circles` dataset

### Week 3 – K-Means Clustering
- Implemented `assign_clusters` and `compute_cluster_centers` from scratch
- Visualized cluster evolution with color-coded scatter plots
- Worked with a 2000-sample synthetic 2D dataset with 3 natural clusters

### Week 4 (Part 1) – Probabilistic Modelling & MLE
- Maximum Likelihood Estimation for Bernoulli and Categorical distributions
- Studied the effect of dataset size on MLE accuracy
- Sampled from biased distributions using NumPy's random number generator

### Week 4 (Part 2) – Gaussian Mixture Models & EM Algorithm
- Sampled from a 3-component GMM step by step
- Implemented the full EM algorithm: Initialization → E-step → M-step → Convergence
- Estimated GMM parameters (means, variances, mixing coefficients) from data

### Week 5 – Linear & Kernel Regression
- Derived closed-form OLS weights using the pseudo-inverse on the Boston Housing dataset
- Built prediction and RMSE loss functions from scratch
- Implemented Kernel Regression and compared train vs. test performance

### Week 6 – Regression Pipeline & Data Preprocessing
- Implemented custom `shuffle_data` and `train_test_split` functions from scratch
- Built a complete regression pipeline on the Diabetes dataset
- Added bias (dummy) features and evaluated model performance with RMSE

### Week 7 – Decision Trees & KNN
- Implemented `entropy` and `information gain` functions from scratch
- Analysed decision stumps and studied IG as a function of split threshold
- Explored KNN classification and decision boundary visualizations

---

## 🛠️ Tech Stack

- **Language:** Python 3
- **Libraries:** NumPy, Matplotlib, Keras (datasets only)
- **Environment:** Google Colab / Jupyter Notebook

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/Machine_Learning_Techniques-Semester_Assignments-.git
   ```
2. Open any `.ipynb` file in [Google Colab](https://colab.research.google.com/) or Jupyter Notebook.
3. Run cells sequentially — each notebook is self-contained.

---

## 👤 Author

**Ganapa Shiva Sai Akhilesh Reddy**  
B.Tech (Hons.) Electrical Engineering – IIT Kharagpur  
B.S. Data Science & Applications – IIT Madras  
📧 gssakhileshreddy2005@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/akhilesh-reddy-9381742a1)

---

> *These assignments are part of the graded coursework for the MLT course at IIT Madras. The implementations are done independently for learning purposes.*
