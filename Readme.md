# Optimized Product Recommendation for Enhanced User Experience on Amazon

## 📘 Overview

This project aims to enhance the product recommendation system for Amazon users, particularly within the electronics category. By utilizing advanced data analytics and machine learning algorithms, the goal is to personalize product suggestions to better align with individual user preferences, thereby improving user experience and engagement.

## 📦 Dataset

The dataset used is from the [Amazon Reviews dataset](http://jmcauley.ucsd.edu/data/amazon/). This dataset includes:

* **UserId**: Unique identifier for each user.
* **ProductId**: Unique identifier for each product.
* **Rating**: Rating given by a user to a product.
* **Timestamp**: Time at which the rating was given.

These attributes are used to analyze user behavior and develop a recommendation engine that provides tailored product suggestions.

## 🛠️ Features

* Data loading and preprocessing
* Exploratory Data Analysis (EDA)
* Popularity-based and collaborative filtering models
* Performance evaluation using RMSE
* Visualizations comparing model outputs

## 📊 Methods

* **Data Preprocessing**: Includes removing duplicates, formatting timestamps, and evaluating data sparsity.
* **Modeling**:

  * **Popularity-Based Model**: Recommends top-rated products.
  * **Collaborative Filtering**: Uses user-based or item-based approaches like KNN or SVD to predict ratings.
* **Evaluation**:

  * RMSE comparison to measure model accuracy.

## 💡 Results

* **Popularity-Based Model RMSE**: \~1015.91 (less effective)
* **Collaborative Filtering Model RMSE**: \~3.50 (more accurate)
* Collaborative filtering significantly outperformed popularity-based methods, showcasing its ability to personalize recommendations effectively.

## 🛠️ Technologies Used

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn
* Jupyter Notebook

## 🚀 Getting Started

### Prerequisites

* Python 3.8+
* Jupyter Notebook
* Install dependencies:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

### Running the Notebook

```bash
git clone https://github.com/yourusername/repo-name.git
cd repo-name
jupyter notebook "Amazon recommendation system.ipynb"
```