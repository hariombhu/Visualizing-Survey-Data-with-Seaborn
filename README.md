# Visualizing-Survey-Data-with-Seaborn

This project visualizes synthetic survey data using Python libraries such as *Pandas, **Seaborn, and **Matplotlib*. The goal is to highlight trends in satisfaction levels and opinions across different departments using insightful charts.


## Problem Statement

Analyze survey data using visualizations to highlight key trends and opinions.

## Expected Outcomes:
- Countplot: Distribution of response types
- Pie Chart: Distribution of satisfaction levels (1–5)
- Bar Plot: Average satisfaction rating per department

---

🧾 Dataset

The dataset used in this project is a self-generated CSV file with 1000 entries, simulating survey responses. It contains the following columns:

| Column           | Description                                      |
|------------------|--------------------------------------------------|
| RespondentID   | Unique ID for each respondent                    |
| Department     | Department name (e.g., HR, IT, Marketing, etc.)  |
| SatisfactionLevel | Satisfaction rating on a scale of 1 to 5      |
| ResponseType   | Overall response sentiment: Positive, Neutral, Negative |

📁 File: survey_data_1000.csv



##  Technologies Used

- Python 3.x  
- Pandas  
- Seaborn  
- Matplotlib  

---
 📊 Visualizations

The project includes the following visualizations:

1. **Response Count by Type
   - Shows how many respondents are Positive, Neutral, or Negative
2. Pie Chart of Satisfaction Levels
   - Displays percentage distribution across 1–5 rating levels
3. Bar Chart of Avg. Satisfaction per Department
   - Highlights which departments are performing better in satisfaction


##  How to Run

1. Clone this repository
2. Install required packages:
   ```bash
   pip install pandas seaborn matplotlib
