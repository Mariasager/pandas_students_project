# Student Performance Finder

This is a small **Pandas practice project** made in Jupyter Notebook.  
It analyzes student marks, cleans missing data, calculates totals and grades, and finds top performers.

## Dataset
The dataset is very small and included in the project:

Name,City,Math,Science,English
Ali,Lahore,85,90,88
Sara,Karachi,92,87,95
Hassan,Lahore,78,,80
Ayesha,Islamabad,88,92,89
Bilal,Karachi,95,85,94
Sana,Lahore,,91,86

##  What the project does
- Reads data from `students.csv`
- Cleans missing values by replacing them with subject averages
- Adds **Total** and **Grade** columns
- Finds:
  - Top scorer in each city
  - Average marks per subject per city
  - Overall best student
- Creates a simple **pivot table**
- Saves cleaned data to `students_cleaned.csv`
- Provides a function `find_student(name)` to search for a student

##  Project files
- `students.csv`:the dataset  
- `student_analysis.ipynb`: Jupyter Notebook with all code and results  
- `students_cleaned.csv` :cleaned dataset (saved by the notebook)  
- `README.md` : this file  

##  How to use
1. Open `student_analysis.ipynb` in Jupyter Notebook.  
2. Run the cells one by one.  
3. Check results, or use `find_student("Sara")` to search for a student.  

That’s it. A very simple Pandas practice project.
