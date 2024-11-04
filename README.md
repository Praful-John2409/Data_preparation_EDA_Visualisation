# **Data Preparation, EDA, and Visualization Repository**

Welcome to the **Data Preparation, EDA, and Visualization** GitHub repository! This repository showcases the complete end-to-end workflow for preparing, exploring, visualizing, and building machine learning models on a structured dataset. 

**Link to Colab** [Data Preparation, EDA, and Visualization on Tabular dataset](https://colab.research.google.com/drive/1hfH0KqFEfvvr0B-Kf0bCKfPoYiFs10pp?usp=sharing)
[Data Preparation, EDA, and Visualization on Time Series dataset](https://colab.research.google.com/drive/1BGfiqksR1bK7_NymYLBMHPkzeSn02EaR?usp=sharing)

---

## **Dataset Overview**

The dataset used in this project focuses on **musical track features** and **genres**, providing numerical and categorical attributes. Below is a summary of the dataset:

- **Attributes:**  
  - **Danceability:** A float value describing how suitable the track is for dancing.
  - **Energy:** A measure of intensity and activity within the song.
  - **Loudness:** The overall loudness of the track in decibels.
  - **Speechiness:** The presence of spoken words in the track.
  - **Acousticness:** Likelihood that the track is acoustic.
  - **Instrumentalness:** Describes how much of the track is purely instrumental.
  - **Tempo:** Beats per minute (BPM) of the track.
  - **Valence:** A measure of musical positivity or happiness.
  - **Genres:** Categorical labels representing the type of music (e.g., Trap, EDM, Hardstyle).

- **Dataset Size:**  
  - **Rows:** 42,305
  - **Columns:** 28 (after preprocessing)
  
This dataset allows for deep exploration of **musical patterns, genre classification, and data preparation workflows** using various AutoML models.

---

## **Colab Notebook Overview**

The Colab notebook demonstrates an **end-to-end workflow** for preparing the dataset, performing **exploratory data analysis (EDA)**, and building **machine learning models** using **AutoML techniques**. 

### **Steps Covered in the Colab:**

1. **Data Loading and Preprocessing:**
   - Loaded the **final preprocessed dataset**.
   - Ensured **feature scaling** using **StandardScaler**.
   - Removed **outliers** and ensured high-quality data for model building.

2. **Exploratory Data Analysis (EDA) and Visualization:**
   - Conducted **distribution analysis** on numerical features (e.g., danceability, energy).
   - Created a **correlation heatmap** to identify feature relationships.
   - Visualized **top genres** with bar plots to understand data distribution.

3. **AutoML Model Building with AutoVIML:**
   - **Feature selection and hyperparameter tuning** were automated using **AutoVIML**.
   - Built multiple models and selected the **best-performing ensemble model**.
   - Achieved an outstanding **accuracy score of 99%** on the test set.

4. **Model Evaluation:**
   - Evaluated the model’s performance using **accuracy metrics**.
   - Addressed potential **feature mismatches** to ensure smooth predictions on the test set.

---

## **Getting Started**

### **Clone the Repository:**

To get started with the code and data, **clone the repository** using the following command:

```bash
git clone https://github.com/Praful-John2409/Data_preparation_EDA_Visualisation.git
```

### **Environment Setup:**

Make sure you have the required libraries installed. Run the following commands in your Colab environment:

```bash
!pip install autoviml numpy==1.22.4 scipy==1.9.3 matplotlib==3.5.3
```

---

## **How to Use the Notebook**

1. **Open the Colab notebook** located in the `colabs/` folder.
2. **Upload the dataset** found in the `datasets/` folder into your Colab environment.
3. **Follow the steps** inside the notebook to:
   - Perform **EDA and visualizations**.
   - Train and evaluate **AutoML models** using AutoVIML.
4. Modify the notebook as needed to **extend the workflow** for future tasks.

---
