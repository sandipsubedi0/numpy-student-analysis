# NumPy Student Analysis — numpy_1.ipynb

A hands-on NumPy learning project that analyzes a dataset of 500 students
(Math, Science, English scores + Hours Studied) and computes each student's
Total Score, Average, Pass/Fail Result, Grade, and CGPA using the NEB grading scale.

## What this notebook covers
- Loading CSV data with pandas and converting columns to NumPy arrays
- Basic array operations and broadcasting
- Descriptive statistics — mean, median, std, min, max
- Sorting arrays and finding extremes with `argmax` / `argmin`
- Boolean filtering and multi-condition masking
- 2D arrays with `column_stack` and `axis` parameter
- Reshaping arrays with `reshape`
- `np.unique`, `np.percentile`, `np.clip`, `np.where`, `np.select`
- Correlation analysis with `np.corrcoef`
- Saving final results to CSV

## Dataset
`student_data.csv` — 500 rows, 6 columns (Student_ID, Age, Math_Score, Science_Score, English_Score, Hours_Studied)

## Output
`student_results.csv` — same data extended with Total Score, Average Score, Result, Grade, and CGPA columns

## Tools
Python · NumPy · Pandas
