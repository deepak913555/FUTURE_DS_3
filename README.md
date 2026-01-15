# 🎓 Student Feedback Sentiment Analysis  
📊 College Event Feedback Analysis | Data Science Internship Project  

---

## 📌 Project Overview
This project focuses on analyzing student feedback collected after college events such as workshops, seminars, and cultural programs.  
The objective is to transform **raw student feedback** into **actionable insights** using **Natural Language Processing (NLP)** and **data visualization techniques**.

The analysis helps institutions understand:
- Overall student satisfaction
- Trends in sentiment over time
- Relationship between ratings and feedback
- Key areas that require improvement

---

## 🎯 Objectives
- Clean and preprocess real-world feedback data
- Perform sentiment analysis on textual comments
- Classify feedback into **Positive**, **Neutral**, and **Negative**
- Visualize sentiment trends and rating patterns
- Provide data-driven recommendations for event improvement

---

## 📂 Dataset Description
The dataset consists of student feedback collected through surveys (simulated/Google Form-based).

### Key Columns:
- **Event_Name** – Name of the event  
- **Event_Type** – Workshop / Seminar / Cultural  
- **Department** – Hosting department  
- **Rating** – Student rating (1–5 scale)  
- **Feedback** – Textual feedback provided by students  
- **Date** – Review submission date (simulated for trend analysis)

---

## 🧠 Methodology

### 1️⃣ Data Cleaning
- Removed missing feedback entries
- Standardized column formats
- Converted date column to datetime format

### 2️⃣ Sentiment Analysis (NLP)
- Used **TextBlob** to compute sentiment polarity  
- Polarity interpretation:
  - `> 0` → Positive  
  - `= 0` → Neutral  
  - `< 0` → Negative  

### 3️⃣ Visualization & Analysis
- Sentiment distribution (Bar & Pie charts)
- Monthly sentiment trend analysis
- Event Type vs Rating comparison (Boxplot)
- Word clouds for positive and negative feedback

---

## 📊 Tools & Technologies Used
- **Python**
- **Pandas & NumPy** – Data cleaning and manipulation
- **TextBlob** – Sentiment analysis (NLP)
- **Matplotlib & Seaborn** – Data visualization
- **WordCloud** – Text pattern visualization
- **Jupyter Notebook / Google Colab**

---

## 🔍 Key Insights
- Majority of student feedback is **positive**, indicating overall satisfaction
- Workshops tend to receive more consistent and higher ratings
- Negative feedback frequently highlights:
  - Long event duration
  - Poor management
  - Lack of engagement
- Strong correlation observed between **sentiment polarity** and **numeric ratings**

---

## 📈 Dashboard Preview
The project includes a combined dashboard showcasing:
- Monthly sentiment trends
- Sentiment distribution
- Sentiment percentage breakdown
- Event Type vs Rating comparison

---

## ✅ Recommendations
- Reduce duration of seminars and improve interaction
- Enhance event planning and time management
- Collect feedback regularly and monitor trends using NLP dashboards
- Use data-driven insights for continuous improvement

---

## 🚀 Conclusion
This project demonstrates how **data science and NLP** can be applied to analyze unstructured student feedback and support better decision-making in educational institutions.

---

## 📎 Future Improvements
- Integrate real-time Google Form responses
- Use advanced NLP models (VADER / BERT)
- Build an interactive Power BI or Streamlit dashboard

---

📌 *This project was developed as part of a Data Science & Analytics internship to simulate real-world feedback analysis scenarios.*
