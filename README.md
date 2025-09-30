# User Engagement Analytics with Python

## 📌 Overview
This project focuses on analyzing **user engagement metrics** such as sessions, users, engagement rate, event counts, and average engagement time across different digital channels.  
The analysis was performed using **Python (Pandas, Matplotlib, Seaborn)** within a Jupyter Notebook.

The goal of this project is to:
- Clean and preprocess engagement data.
- Explore patterns in user sessions and channel performance.
- Visualize trends and insights using data visualization techniques.

---

## 📊 Dataset
The dataset (`data-export.csv`) contains:
- **Channel Group** – Traffic source/channel category.  
- **Date + Hour** – Timestamp of activity.  
- **Users** – Number of unique users.  
- **Sessions** – Number of sessions initiated.  
- **Engaged Sessions** – Sessions with significant user interaction.  
- **Engagement Rate** – Proportion of engaged sessions.  
- **Event Count** – Number of tracked events.  
- **Average Engagement Time per Session** – User activity duration.  

---

## 🔍 Analysis Performed
1. **Data Cleaning**
   - Handled headers and missing values.
   - Converted timestamps to datetime format.
   - Converted numeric columns for accurate computation.

2. **Exploratory Data Analysis (EDA)**
   - Sessions & users trend over time.
   - Total users by channel.
   - Average engagement time by channel.
   - Engagement rate distribution by channel.
   - Engaged vs non-engaged sessions.

3. **Visualizations**
   - Line plots for time-series trends.
   - Bar plots for channel-wise engagement.
   - Box plots for distribution analysis.

---

## 🛠️ Tools & Libraries
- **Python 3.x**
- **Pandas** – Data manipulation & cleaning.
- **NumPy** – Numerical operations.
- **Matplotlib & Seaborn** – Data visualization.
- **Jupyter Notebook** – Interactive analysis.

---

## 📈 Results & Insights
- Certain channels consistently drive higher **user traffic**.  
- Engagement rate varies significantly by **channel group**.  
- Time-of-day trends highlight peak session hours.  
- Average engagement time is not uniform across channels.  

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
      git clone https://github.com/ruchira2424/Engagement_Metrics_Dashboard-Python-Seaborn.git
      cd Engagement_Metrics_Dashboard-Python-Seaborn

 
