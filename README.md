# AI-Skill-Assessment-Agent
AI-powered system that evaluates resume vs job description, identifies skill gaps, and generates a learning plan with interview simulation.
## ⚠️ Note

Due to API quota limits, the system is running in offline mode.  
However, the architecture is designed to integrate with LLM APIs for dynamic skill assessment and learning plan generation in a production environment.
## 🏗 Architecture

![Architecture](architecture.png)
## 📥 Sample Input

Resume:
Python, SQL, EXCEL, powerBI

Job Description:
We are hiring a Data Analyst with strong foundational skills in data analysis and problem solving.

Responsibilities:
- Perform exploratory data analysis (EDA)
- Clean and preprocess datasets using Python
- Write SQL queries to extract and manipulate data
- Build basic dashboards and reports
- Analyze trends and generate insights

Required Skills:
- Python (Pandas, NumPy)
- SQL
- Data Cleaning & EDA
- Basic Statistics
- Excel

Nice to Have:
- Power BI or Tableau
- Machine Learning basics
- Communication skills

## 📤 Sample Output

Score: 50%

Matched Skills:
- Python
- SQL
- PowerBi
- Excel

Missing Skills:
- Machine Learning
- Tableaue
- Statistics
