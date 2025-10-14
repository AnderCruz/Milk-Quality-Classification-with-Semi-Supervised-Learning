# Milk Quality Classification with Semi-Supervised Learning

## 📌 Project Overview

This project, developed by **Nowa Analytics**, focuses on building semi-supervised classification models to assess **milk quality**.
We were contracted by a **dairy industry** to help guarantee the quality of milk used in their products.

Using **machine learning**, we classify milk samples into three categories:

* **Low Quality**
* **Medium Quality**
* **High Quality**

Since the dataset contains both **labeled and unlabeled samples**, we applied **semi-supervised learning techniques** such as:

* ✅ Self-Training with labeled + unlabeled data
* ✅ Label Propagation (transductive learning)
* ✅ Supervised baselines for performance comparison



## 📊 Dataset

The dataset was provided in a CSV file named **`qualidade_leite.csv`**, containing **1,059 entries** with the following features:

| Column          | Description                                                           |
| --------------- | --------------------------------------------------------------------- |
| **pH**          | pH level of the milk (continuous)                                     |
| **Temperature** | Temperature of the sample (°C)                                        |
| **Taste**       | Taste quality score                                                   |
| **Odor**        | Odor quality score                                                    |
| **Fat**         | Fat content                                                           |
| **Turbidity**   | Milk turbidity                                                        |
| **Color**       | Visual color quality                                                  |
| **Quality**     | Target variable (Low, Medium, High) – partially labeled (424 samples) |

📌 Note: Only a portion of the dataset has labels, which makes it ideal for **semi-supervised approaches**.



## ⚙️ Project Objectives

1. Train classification models using **labeled data**.
2. Understand and apply **semi-supervised learning** concepts.
3. Generate pseudo-labels for unlabeled samples.
4. Apply **Self-Training** strategy with labeled + unlabeled data.
5. Explore **transductive learning** using **Label Propagation**.
6. Compare the results against fully supervised models.



## 🛠️ Technologies Used

* **Python 3.11+**
* **Pandas & NumPy** – Data processing
* **Scikit-learn** – Classification, Self-Training, Label Propagation
* **Matplotlib & Seaborn** – Data visualization
* **Jupyter Notebook** – Experiment tracking



## 📈 Expected Results

* Improved classification performance using **semi-supervised approaches**.
* Demonstration of how **unlabeled data** can boost model accuracy.
* Comparison between **Self-Training, Label Propagation, and supervised baselines**.



## 👨‍💻 Authors

Project developed by **Nowa Analytics**
🚀 Data Science Consulting | Machine Learning Solutions

