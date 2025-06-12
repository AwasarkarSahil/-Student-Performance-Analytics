# 🎓 Student Participation Analytics - At-Risk Student Detection

This project uses Exploratory Data Analysis (EDA) techniques to identify at-risk students based on their engagement metrics such as hands raised in class, visited learning resources, announcements viewed, and discussion participation.

## 📌 Objective

To help educational institutions identify students who may be at academic risk early, enabling timely intervention.

## 📊 Dataset

- Source: [Kaggle Student Performance Dataset](https://www.kaggle.com/datasets/aljarah/xAPI-Edu-Data)
- Format: CSV
- Key Features Used:
  - `HandsRaised`
  - `VisITedResources`
  - `AnnouncementsView`
  - `Discussion`
  - `Performance` (target for risk identification)

## 📈 Key Features

- ✅ Correlation heatmap of participation metrics.
- ✅ Filtering of students with low engagement.
- ✅ Automatic identification of at-risk students.
- ✅ Exports at-risk student list to CSV (`at_risk_students.csv`).

## 📌 At-Risk Criteria

Students are considered **at-risk** if:

- Hands Raised < 10
- Visited Resources < 50
- Performance = "L" (Low)

## 🛠️ Tools & Libraries

- Python 🐍
- Pandas
- Seaborn
- Matplotlib
- Jupyter Notebook (or any Python IDE)

**Saved CSV File**  
- `at_risk_students.csv` contains filtered student data.

## 🚀 Getting Started

```bash
pip install pandas matplotlib seaborn
