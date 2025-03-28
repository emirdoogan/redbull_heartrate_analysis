# ❤️ Red Bull & Heart Rate Analysis

This project explores the **relationship between Red Bull consumption and heart rate**, and how different **age groups** and **sex** categories may respond to it. The study involves real-world survey data, statistical testing, and data visualization using Python and Tableau.

---

## 🎯 Goals

- Determine if Red Bull consumption significantly affects heart rate.
- Compare heart rate changes across **age groups**.
- Examine if **sex (male/female)** influences the result.

---

## 📊 Dataset Overview

- **Source:** [Kaggle – Omar Sobhy’s dataset](https://www.kaggle.com/datasets/omarsobhy14/red-bull-vs-heart-rate)
- **Participants:** 120 (subset of 281 original entries)
- **Collection Method:** Face-to-face surveys
- **Demographics:** Egyptian volunteers
- **Data Fields:** Age group, sex, heart rate before and after consumption

---

## 🧼 Data Cleaning

- ✔️ No missing values
- ✔️ Outlier detection via **IQR** and **Z-score**
- ✔️ Verified participant count: 120

---

## 🧪 Analysis Summary

- **Paired sample t-tests** used to compare heart rate before and after consumption.
- Subgroup analysis by age and sex.
- Multiple visualizations created to show overall and segmented trends.

---

## 📈 Visual Highlights

### 1. 📊 Heart Rate Distribution – Before Red Bull

![Heart Rate Before](redbull_heart_analysis/Individual%20Changes%20in%20Heart%20Rate%20Before.png)

Shows a left-skewed distribution of heart rates prior to Red Bull consumption.

---

### 2. 📊 Before & After Comparison by Age Group and Sex

![Heart Rate Change by Group](redbull_heart_analysis/Change%20in%20Heart%20Rate%20Before%20and%20After%20Consumption.png)

The visual below shows how **heart rate increased** for all subgroups, with a slightly greater effect among **older males**.

---

### 3. 🌡️ Heatmap of Heart Rate Differences

![Heart Rate Difference Heatmap](redbull_heart_analysis/Difference%20in%20Heart%20Rates%20After%20Red%20Bull%20by%20Age%20Group%20and%20Gender.png)

This heatmap summarizes the **average heart rate increase** after Red Bull across age-sex segments. Highest increase observed: **Males aged 46–59**.

---

## 📊 Interactive Tableau Dashboard

### 📍 Summary Dashboard

👉 [Click here to view and interact with the full Tableau Dashboard](https://public.tableau.com/app/profile/emir.do.an/viz/RedBullandHeartRateVisualization/SummaryDashboardofRedBullConsumptionandHeartRate)

Explore all charts and filters directly from your browser. No login required.

---

## 🧰 Tools & Technologies

- Python (`pandas`, `numpy`, `matplotlib`, `seaborn`, `scipy`)
- Jupyter Notebook (`redbull_heart_rate.ipynb`)
- Tableau (for interactive dashboard)
- Excel & Word (for documentation)

---

## 📄 License

This project is for educational and analytical purposes only.

---

## 🙋‍♂️ Author

**Emir Doğan** 


---
