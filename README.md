# 📱 Google Play Store Data Analysis & Cleaning

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Library-Pandas-orange)](https://pandas.pydata.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This project focuses on the **comprehensive data cleaning and Exploratory Data Analysis (EDA)** of the Google Play Store dataset.

---

## Dataset Information
The data used in this project is sourced from Kaggle:
🔗 **[Google Play Store Apps Dataset](https://www.kaggle.com/datasets/lava18/google-play-store-apps)**

---

## How to Use / Nasıl Kullanılır?

To run this project locally or on Google Colab, follow these steps:

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/Talhaozt/GooglePlayStore-Analysis-Project.git](https://github.com/Talhaozt/GooglePlayStore-Analysis-Project.git)
    ```
2.  **Install Required Libraries:**
    Ensure you have the following libraries installed:
    ```bash
    pip install pandas numpy matplotlib seaborn
    ```
3.  **Run the Analysis:**
    *   Open `Google_Play_Store_Apps_Dataset.ipynb` in **Google Colab** or **Jupyter Notebook**.
    *   Make sure `googleplaystore.csv` is in the same directory as the notebook.
    *   Run all cells to see the cleaning process and visualizations.

---

## Data Cleaning Highlights
*   **Invalid Row Removal:** Dropped corrupted rows (e.g., row 10472) to maintain dataset logic.
*   **Type Conversion:** Converted `Reviews`, `Installs`, and `Price` to numeric values.
*   **Size Standardization:** Converted 'M' (Megabytes) and 'k' (Kilobytes) into a uniform float format.
*   **Missing Value Imputation:** Replaced "Varies with device" and other nulls using **statistical median**.

---

## Key Insights from EDA
*   **Rating Distribution:** Most apps have a rating between **4.0 and 4.5**.
*   **Category Analysis:** Identified market leaders in the top 5 categories (Game, Communication, Tools, etc.).
*   **Time Series:** Analyzed update trends by extracting Year, Month, and Day.

---

## 🇹🇷 Özet (Turkish Summary)
Bu proje, 10.000'den fazla Google Play Store uygulama verisinin temizlenmesi ve keşifsel veri analizi (EDA) süreçlerini kapsamaktadır. Veri seti üzerinde; hatalı satırların temizlenmesi, sayısal verilerin (indirilme sayısı, fiyat vb.) formatlanması ve eksik verilerin medyan değerleri ile doldurulması işlemleri yapılmıştır. Bu çalışma, ham verinin bir makine öğrenmesi modeline girmeden önceki ön işleme aşamalarını detaylıca sunar.

---
