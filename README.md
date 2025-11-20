# Airline Crew Scheduling – Backtracking & Constraint Satisfaction

This project implements a simplified Airline Crew Scheduling model using  
**Backtracking + Constraint Satisfaction**, demonstrating why the real-world  
version of this problem is NP-hard.

---

## 📌 Features
- Backtracking-based crew assignment
- Minimum rest-time constraint checking
- No overlapping flights
- Gantt chart visualization (Matplotlib)
- Experimental profiling:
  - Execution time (4–10 flights)
  - Memory usage (memory_profiler)
  - Recursive call count
- Time/Memory complexity plots

---

## 📂 Repository Structure
airline_crew_scheduling/

│
├── README.md

├── crew_scheduling_notebook.ipynb

├── requirements.txt

├── .gitignore

└── images/

├── gantt_chart.png

├── time_plot.png

├── memory_plot.png

└── recursion_plot.png

📈 Performance Insights

Why Backtracking Becomes Infeasible

Backtracking explores choices of the form:

𝑂
(
𝑘
×
2
𝑛
)
n = number of flights

k = number of crew members

It becomes infeasible beyond 10–12 flights due to:

Exponential branching

Deep recursion

Constraint propagation at each level

🔧 Technologies Used
Python
Matplotlib
memory_profiler
Backtracking & Constraint Satisfaction
Google Colab / Jupyter Notebook
