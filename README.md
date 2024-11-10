# **Data Preparation, EDA, and Visualization Repository**

Welcome to the **Data Preparation, EDA, and Visualization** GitHub repository! This repository showcases a comprehensive end-to-end workflow for preparing, exploring, visualizing, and building machine learning models on two distinct types of datasets: a **tabular dataset of musical track features and genres** and a **time series dataset focused on retail sales data**.

## **Colab Notebooks**

1. **[Data Preparation, EDA, and Visualization on Tabular Dataset](https://colab.research.google.com/drive/1hfH0KqFEfvvr0B-Kf0bCKfPoYiFs10pp?usp=sharing)**
2. **[Data Preparation, EDA, and Visualization on Time Series Dataset](https://colab.research.google.com/drive/1BGfiqksR1bK7_NymYLBMHPkzeSn02EaR?usp=sharing)**

---
## Youtube video 
click [here](https://youtube.com/playlist?list=PLkZIndjUMqFWnrI-rfNxrHactjoZ0oNL9&si=G13sD6-n1vMCBvry) for the youtube playlist that covers the exaplanation of the Colabs 
---

## **Dataset Overviews**

### **1. Tabular Dataset: Musical Track Features and Genres**

The first dataset includes various numerical and categorical attributes that describe the characteristics of musical tracks and their genres. This dataset is perfect for genre classification and analyzing musical patterns.

- **Attributes:**
  - **Danceability, Energy, Loudness, Speechiness, Acousticness, Instrumentalness, Tempo, Valence**
  - **Genres:** Categorical labels representing the type of music (e.g., Trap, EDM, Hardstyle).
- **Dataset Size:**  
  - **Rows:** 42,305
  - **Columns:** 28 (after preprocessing)

### **2. Time Series Dataset: Retail Sales Data**

The second dataset comprises time series data related to retail sales, enriched with additional features like holidays, oil prices, and transactions. This dataset enables exploration of sales patterns, holiday effects, and other influencing factors.

- **Attributes:**
  - **Date, Store Number, Sales, Family (Product Categories), On Promotion**
  - **Supplementary Data:** Oil prices, holiday events, transactions at stores, and store details.
- **Dataset Size:**  
  - **Multiple CSV Files** containing varying numbers of rows and columns, with data for thousands of transactions over multiple years.

---

## **Colab Notebook Overviews**

### **Tabular Data Workflow:**

1. **Data Loading and Preprocessing:**
   - Cleaned and scaled the dataset using `StandardScaler`.
   - Removed outliers to ensure data quality for model building.
  
2. **Exploratory Data Analysis (EDA):**
   - Analyzed the distributions of numerical features like danceability and energy.
   - Created a correlation heatmap to understand feature relationships.
   - Visualized the most frequent genres using bar plots.

3. **Model Building with AutoVIML:**
   - Automated feature selection and hyperparameter tuning.
   - Trained multiple models and selected the best-performing ensemble model.
   - Achieved an impressive accuracy score of **99%** on the test set.

### **Time Series Data Workflow:**

1. **Data Loading and Integration:**
   - Merged data from different CSV files (e.g., oil prices, holidays, transactions).
   - Addressed missing values and performed initial data quality checks.

2. **Exploratory Data Analysis:**
   - Visualized time series trends, seasonal patterns, and anomalies.
   - Examined sales fluctuations around holidays and the impact of oil prices.
   - Explored store-wise sales trends and analyzed high-transaction periods.

3. **Time Series Forecasting:**
   - Applied preprocessing techniques to prepare the data for forecasting.
   - Developed and evaluated models to predict future sales based on historical data.

---

## **Getting Started**

### **Clone the Repository:**

```bash
git clone https://github.com/Praful-John2409/Data_preparation_EDA_Visualisation.git
```

### **Environment Setup:**

Make sure you have the required libraries installed. Use the following command in your Colab environment:

```bash
!pip install autoviml numpy==1.22.4 scipy==1.9.3 matplotlib==3.5.3
```

---

## **How to Use the Notebooks**

1. **Open the Colab notebook** for the desired dataset in the `colabs/` folder.
2. **Upload the respective dataset** from the `datasets/` folder into your Colab environment.
3. **Follow the step-by-step instructions** to explore the data, perform visualizations, and build models.
4. Feel free to modify and extend the notebooks for your own analyses.

---
