# 📊 Facebook Live Sellers' Engagement Analysis

This project analyzes how the **time of uploading Facebook Live posts** influences user engagement — measured in reactions, comments, and shares. The dataset includes over 7,000 posts by fashion and cosmetics sellers in Thailand.

---

## 🎯 Objective

- Examine how the **time of post upload** (hour, day, month) affects engagement.
- Explore the **correlation between reactions, comments, and shares**.
- Provide actionable **recommendations for Facebook Live sellers** to improve their posting strategies.

---

## 📁 Dataset Overview

- **Total Rows:** 7,050 posts  
- **Attributes:** 14 columns including:
  - `status_published` – Date & time of post
  - `num_reactions`, `num_comments`, `num_shares`
  - `status_type`, `num_likes`, `num_loves`, `num_wows`, etc.

---

## 🔍 Analysis Questions

1. How does the **time of upload** affect the number of reactions?
2. Is there a **correlation** between reactions, comments, and shares?
3. How can sellers **leverage this information** for better engagement?

---

## 🧠 Methodology

- Extracted `hour`, `day_of_week`, and `month` from `status_published`.
- Analyzed trends in engagement based on time features.
- Computed **Pearson correlation** between engagement metrics.
- Visualized relationships using heatmaps and time-based plots.

---

## 📊 Key Findings

| Metric Comparison | Correlation (Pearson) | Insight |
|-------------------|------------------------|---------|
| Reactions vs Comments | **0.85** | Strong positive correlation |
| Reactions vs Shares   | **0.65** | Moderate positive correlation |

- Posts uploaded during **evening hours** and on **weekends** show **higher engagement**.
- **Reactions and comments** are closely linked — engaging posts get both.
- **Shares** moderately follow reaction counts.

---

## 📌 Recommendations

- ⏰ **Optimal Timing:** Post in the evening and on weekends for better reach.
- 🎯 **Content Strategy:** Focus on highly interactive content to increase reactions, which drive comments and shares.
- 📈 **Data-Driven Posting:** Use time-based insights to schedule posts for maximum impact.

---

## 📈 Visualizations

- Correlation matrix of engagement metrics
- Bar plots of average reactions by hour, day, and month
- Time-distribution graphs of posts vs engagement

---

## 💻 How to Use

1. **Open the Colab Notebook**:[Open In Colab](https://colab.research.google.com/drive/1TXYzyhqr6ITkOvKQOyWTAr3VNZ28VypC#scrollTo=0RaqiLU0CoDB)  

2. **Upload the Dataset** (`facebook_live_data.csv` or similar)

3. **Run the Notebook** to:
   - Clean and preprocess the data
   - Perform EDA and generate visualizations
   - Interpret correlations and draw insights

---

## 📦 Libraries Used

- `pandas` – Data manipulation  
- `numpy` – Numeric operations  
- `matplotlib` & `seaborn` – Visualizations  
- `datetime` – Time feature extraction  
- `scikit-learn` – Correlation metrics

---

## 📬 Contact

For any feedback, collaboration, or improvements, feel free to reach out or open an issue.

---

> 🚀 This project is ideal for social media marketers, data analysts, and e-commerce sellers looking to optimize Facebook Live strategies using data.
