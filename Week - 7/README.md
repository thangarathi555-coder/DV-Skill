Students Performance Analysis
Project Overview
This project analyzes student exam performance using Python. The dataset contains students' Math, Reading, and Writing scores. The project performs data exploration, statistical analysis, score calculations, and outlier detection.

Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Features
Load and explore the dataset

Display dataset information

Generate descriptive statistics

Check for missing values

Calculate:

Mean
Median
Mode
Standard Deviation
Quartiles
Calculate Total Score and Percentage

Detect outliers using the IQR (Interquartile Range) method

Dataset Information
The dataset contains the following score columns:

Math Score
Reading Score
Writing Score
Statistical Analysis Performed
The program calculates:

Average score of students
Median score
Most frequent score (Mode)
Standard deviation
Quartiles (Q1, Q2, Q3)
Additional Calculations
Total Score
Total Score = Math Score + Reading Score + Writing Score

Percentage
Percentage = (Total Score / 300) × 100

Outlier Detection
Outliers are identified using the IQR method:

Q1 = 25th Percentile
Q3 = 75th Percentile
IQR = Q3 − Q1
Lower Limit = Q1 − 1.5 × IQR
Upper Limit = Q3 + 1.5 × IQR
Any value outside these limits is considered an outlier.

How to Run
Install required libraries:
pip install pandas numpy matplotlib seaborn
Open the Python file.

Update the dataset path if required.

Run the script:

python students_performance_in_exam.py
Output
The program displays:

Dataset information
Summary statistics
Missing value analysis
Total Score and Percentage
Outlier details for each subject
Author
BCA Student Project Students Performance Analysis using Python
