# Wealth Distribution Analysis | 財富分佈數據分析

An exploratory data analysis (EDA) project focused on investigating how net worth varies across different industries and countries. This project uses R and the `tidyverse` suite to clean, visualize, and rank economic data to identify global wealth trends.

本專案透過 R 語言對財富數據進行探索性分析（EDA），研究淨資產在不同產業與國家間的分佈差異。利用 `tidyverse` 進行資料處理與視覺化，找出全球財富趨勢與高價值產業。

---

final.R is the project file.
Others are homework assignments for this class, not related to the project.

---
> **Data Analytics Exploration · 2023**

---

## 🎯 Objective | 分析目標
The primary goal is to identify which industries and countries yield the highest average net worth and to visualize the distribution of wealth to detect potential outliers or market leaders.
核心目標在於識別哪些產業與國家的平均淨資產最高，並透過視覺化手段觀察財富分佈，找出潛在的市場領導者或極端值。

---

## 🛠 Pipeline | 處理流程
1. **Data Cleaning:** Converting industry categories to characters and countries to factors for grouped analysis. / 資料清洗：將產業轉為文字、國家轉為因子，以便進行分組分析。
2. **Exploratory Visualization:** Using Boxplots to observe wealth distribution and detect outliers. / 探索性視覺化：利用盒狀圖觀察財富分佈並識別極端值。
3. **Statistical Aggregation:** Calculating the mean net worth for each sector and nation using `tapply` and `summarise`. / 數據統計：計算各產業與國家的平均淨資產。
4. **Ranking & Sorting:** Ordering data to highlight top-performing markets and industries. / 排序與對比：由高到低排列數據，找出表現最突出的市場與產業。
5. **Experimental 3D Visualization:** (In progress) Implementing 3D scatter plots to observe multi-dimensional relationships. / 3D 視覺化實驗：使用 3D 散佈圖觀察多維度的資料關聯。

---

## 💻 Tech Stack | 技術棧
* **Language:** R
* **Libraries:** `tidyverse` (dplyr, ggplot2), `rgl` (3D Visualization)
* **Techniques:** Descriptive Statistics, Grouped Aggregation, Data Visualization

---

## 📊 Key Analyses | 分析重點
* **Industry Insights:** Comparing the "Mean of Networth" across sectors (e.g., Technology, Finance) to see which industry dominates. / 產業洞察：比較不同產業的平均財富。
* **Country Comparison:** Identifying geographic wealth hubs through horizontal bar charts. / 國家比較：透過水平長條圖找出全球財富聚集地。
* **Distribution Patterns:** Using boxplots to visualize the spread of wealth within specific categories. / 分佈規律：利用盒狀圖視覺化特定類別內的財富擴散情況。

---

## 👥 Author | 作者
* **黃筠茜 (Athena Huang)**

---

## 中文簡介
本專案使用 R 語言進行數據分析，核心任務是針對一份包含淨資產（Networth）、產業（Industry）與國家（Country）的資料集進行清理與探索。流程包含使用 `boxplot` 觀察資產分佈、利用 `barplot` 比較各組平均值，並透過 `dplyr` 的鏈接操作進行數據排名的視覺化。此外，專案中也包含了 3D 繪圖的實驗性程式碼，嘗試從多維角度觀察數據關聯。
