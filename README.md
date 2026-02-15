# Data Mining Course Projects

This repository contains my practice assignments and lab projects from the Data Mining course in the Business Information Systems program. I use this repository as a place to document what I learned while working with real datasets using Python and machine learning libraries. Most of the work here focuses on understanding the data first, then building and evaluating models step by step.

## Project Workflow
In almost every project, I followed a similar workflow:

* **Data Preprocessing**
  Cleaning the dataset, handling missing values, and checking outliers.
* **Exploratory Data Analysis (EDA)**
  Creating visualizations to understand patterns, distributions, and relationships between features.
* **Data Preparation**
  Feature scaling (such as MinMax Scaling) and encoding categorical variables.
* **Modeling**
  Applying several machine learning algorithms and comparing the results.
* **Evaluation**
  Evaluating models using metrics like Accuracy, F1-Score, MAE, RMSE, and R² depending on the task.

## Machine Learning Techniques Used
I practiced three main machine learning approaches:

* **Regression**
  Predicting continuous values such as rating scores or prices.
* **Classification**
  Predicting categories, for example user preference (like / dislike) or customer churn.
* **Clustering**
  Grouping unlabeled data to find hidden patterns using algorithms like K-Means.

## Featured Project: Movie Rating Model Comparison
For the final project, I used the MovieLens dataset to compare several machine learning models on the same dataset.

### Goal
To see how different algorithms perform when predicting movie ratings and user preference.

### Methods Used
* Linear Regression
* Decision Tree
* K-Nearest Neighbors (KNN)
* Support Vector Machine (SVM)
* K-Means Clustering

### Evaluation
* **Regression:** MAE and RMSE
* **Classification:** Accuracy and F1-Score

## What I Learned
* Model performance can change significantly after scaling the data.
* KNN is very sensitive to feature scaling.
* Some models perform well on training data but not on testing data (overfitting).
* Choosing evaluation metrics is as important as choosing the algorithm.

## Tools & Libraries
* **Language:** Python
* **Environment:** Google Colab
* **Libraries:**
  * Pandas & NumPy (data handling)
  * Matplotlib & Seaborn (visualization)
  * Scikit-learn (preprocessing, modeling, evaluation)

## Repository Structure

Setiap folder dalam repositori ini disusun secara sistematis mengikuti alur kerja seorang Data Scientist:

| Nama Folder | Deskripsi Materi & Teknik |
| :--- | :--- |
| **01 - 04 Dasar Data Mining** | Pengantar, teknik pengumpulan data, pemeriksaan statistik awal, dan penentuan objek data. |
| **05 - 06 Data Preprocessing** | Pembersihan data (menangani nilai kosong), penanganan data tidak wajar (outlier), serta teknik pemberian label data manual. |
| **07 & 13 Regression Model** | Implementasi Simple Linear Regression dan Multiple Linear Regression untuk memprediksi nilai angka (kontinu). |
| **08 Clustering Analysis** | Pengelompokan data menggunakan algoritma K-Means, DBSCAN, dan Agglomerative Clustering untuk melihat pola tersembunyi. |
| **11 Decision Tree** | Klasifikasi untuk memprediksi risiko pelanggan berhenti berlangganan (churn) dan menentukan faktor yang paling berpengaruh. |
| **14 K-Nearest Neighbors** | Klasifikasi menggunakan KNN dengan analisis pengaruh normalisasi data (MinMax) terhadap keakuratan model. |
| **15 Support Vector Machine** | Implementasi SVM menggunakan berbagai jenis kernel untuk menentukan kelayakan suatu produk. |
| **Project Perbandingan Model** | Proyek akhir yang membandingkan performa berbagai algoritma (Regresi, Decision Tree, KNN, SVM, dan KMeans) pada satu dataset yang sama. |

## How to Run
Most projects are Jupyter/Colab notebooks:
1. Open [Google Colab](https://colab.research.google.com/)
2. Upload the `.ipynb` file from this repository
3. Upload the required dataset (`.csv`) or connect Google Drive if mentioned in the notebook
4. Run the cells sequentially

---

## Contact
* **GitHub:** [github.com/hapsariputri14](https://github.com/hapsariputri14)
* **LinkedIn:** [Nadya Hapsari Putri](https://www.linkedin.com/in/nadyahapsari-208b94205/)
* **Email:** nadya.hp14@gmail.com
