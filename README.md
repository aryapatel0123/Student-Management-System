# 🎓 Student Performance Management System

A Python-based project designed to manage student records, analyze academic performance, visualize results, and provide personalized recommendations to help students improve their academic habits.

## 📌 About the Project

The **Student Performance Management System** was developed as part of the Python for Data Science subject. It simplifies student record management and evaluates performance using total scores, attendance percentage, weekly self-study hours, and class participation.

The system supports adding, searching, updating, and deleting student records. It also calculates grades, determines pass/fail status, performs statistical analysis, generates visualizations, and provides personalized recommendations based on individual student performance.

## ✨ Features

- **Student Record Management:** Add, search, update, and delete student records.
- **Automatic Grade Calculation:** Assign grades based on students' total scores.
- **Pass/Fail Classification:** Determine results using a passing score of 40.
- **Performance Analysis:** Calculate the average, highest, lowest, and median scores, standard deviation, and average attendance.
- **Grade Analysis:** Display grade distributions and pass/fail counts.
- **Data Visualization:** Generate a scatter plot comparing attendance percentage with total scores.
- **Display Student Records:** View all student information in a structured format.
- **Personalized Recommendations:** Suggest improvements based on scores, attendance, study hours, and class participation.
- **CSV Data Storage:** Save student records in a CSV file for future use.

## 🚀 Topic Beyond the Syllabus

### Automatic Student Performance Recommendation System

This is the additional feature developed beyond the regular syllabus. It uses a **rule-based approach** to identify areas where students may need improvement and provides personalized suggestions.

The system checks four performance indicators:

| Performance Indicator | Condition | Recommendation |
|---|---|---|
| Total Score | Below 40 | Improve academic performance |
| Attendance | Below 75% | Attend classes regularly |
| Weekly Study Hours | Below 8 hours | Increase self-study time |
| Class Participation | Below 5 | Participate more actively in class |

If none of these conditions are triggered, the system encourages the student to maintain their current performance.

This feature transforms student data into practical suggestions rather than simply displaying marks and results.

## 🛠️ Technologies Used

- **Python** — Core programming language
- **Pandas** — Data management and CSV operations
- **NumPy** — Numerical and statistical computations
- **Matplotlib** — Data visualization
- **CSV** — Student record storage
- **OS Module** — Checking whether the dataset file exists

## 📂 Project Structure

```text
Student-Performance-Management-System/
│
├── student_performance.py
├── student_performance.csv
└── README.md
```

*Note: The Python filename is an example. Replace it with your actual filename. The CSV file is created automatically if it does not already exist.*

## ⚙️ Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/Student-Performance-Management-System.git
```

### 2. Navigate to the Project Folder

```bash
cd Student-Performance-Management-System
```

### 3. Install the Required Libraries

```bash
pip install pandas numpy matplotlib
```

### 4. Run the Program

```bash
python student_performance.py
```

Replace `student_performance.py` with your actual Python filename if it differs.

## 🖥️ How to Use

After running the program, a menu appears with the following options:

1. Search Student
2. Add Student
3. Update Student
4. Delete Student
5. Performance Analysis
6. Grade Analysis
7. Visualization
8. Display All Students
9. Student Performance Recommendation
10. Exit

Enter the corresponding number to perform an operation. Follow the prompts to enter student details or view the requested analysis.

## 📊 Data Analysis and Visualization

The project calculates useful statistical measures to summarize student performance, including:

- Average score
- Highest and lowest scores
- Median score
- Standard deviation
- Average attendance percentage
- Grade distribution
- Number of students who pass or fail

It also generates an **Attendance vs Total Score** scatter plot to help explore the relationship between attendance and academic results.

## 🎯 Project Objectives

- Simplify student record management.
- Analyze academic performance using student data.
- Apply statistical methods to understand score distributions.
- Visualize academic performance patterns.
- Identify students' potential improvement areas.
- Provide actionable recommendations through a rule-based system.

## 🔮 Future Enhancements

- Develop a graphical user interface for easier interaction.
- Add login functionality for students and administrators.
- Generate downloadable PDF performance reports.
- Introduce more visualizations and detailed analytics.
- Integrate machine learning to predict academic performance.
- Store records in a database for larger datasets.

## 📚 Learning Outcomes

Through this project, I gained practical experience in Python programming, data manipulation using Pandas, numerical analysis using NumPy, visualization using Matplotlib, CSV file handling, and developing rule-based recommendation logic.

## 🏁 Conclusion

The Student Performance Management System combines student record management, statistical analysis, and data visualization in one Python application. Its Automatic Student Performance Recommendation System adds value by identifying areas for improvement and suggesting practical actions to support better academic performance.

---

**Project:** Student Performance Management System  
**Subject:** Python for Data Science  
**Language:** Python  
**Topic Beyond Syllabus:** Automatic Student Performance Recommendation System

**Developed as an academic project.**
