# Data Science Fundamentals Assessment Report

**Submitted by:** Shivam Kumar  
**Program:** YuvaIntern Data Science Internship Assessment  

---

## Executive Summary

This report covers my complete implementation for the YuvaIntern Data Science Fundamentals Assessment. The goal of this project was to build an end-to-end, reproducible Data Science workflow in a Jupyter Notebook using standard Python libraries. The project goes step-by-step through core Python programming, file handling, statistical computing, hypothesis testing, Pandas data wrangling, and multi-panel visualizations. All work was documented and pushed to GitHub using structured Git commits.

---

## Technologies & Tools Used

- **Language:** Python 3.x
- **Development Environment:** Jupyter Notebook / VS Code
- **Libraries Used:** Pandas, NumPy, SciPy (scipy.stats), Matplotlib, Seaborn
- **Version Control:** Git & GitHub

---

## Section-by-Section Implementation Summary

### 1. Python Programming Basics
In the first section, I focused on writing clean, modular Python code. I built custom functions to process data dynamically and added `try-except` blocks to handle unexpected inputs or runtime errors smoothly without crashing the script.

### 2. Data Structures & File Handling
I worked with basic Python data structures including Lists, Dictionaries, Sets, and Tuples to store student records. For file handling, I used Python’s context manager (`with` statement) to read and write files safely without leaving open file pointers in memory.

### 3. Statistical Foundations & Inferential Testing
This section focused on understanding the numbers behind the data:
- **Descriptive Stats:** Calculated key values including Mean (~82.5), Median (85.0), Mode (85), Variance (126.25), Standard Deviation (11.24), and Percentiles.
- **Distributions:** Simulated Normal, Binomial, and Poisson probability distributions using `np.random.seed(42)` for consistent output.
- **Statistical Testing:** Ran a two-sample t-test which gave a statistically significant result ($p < 0.05$), proving noticeable variation between test groups. I also calculated a Pearson correlation coefficient ($r \approx 0.9953$).

### 4. Data Manipulation with Pandas
Using Pandas, I created structured DataFrames and performed standard checks with `.head()`, `.info()`, and `.describe()`. I practiced precise indexing with `.loc` and `.iloc`, applied boolean filters to extract target student records, grouped metrics by department using `.groupby()`, and handled missing data by imputing null entries with column mean values.

### 5. Data Visualization
I created a 2x2 multi-panel plot layout using Matplotlib and Seaborn to visualize patterns in the data:
- A Bar Plot comparing average scores across departments.
- A Histogram with a KDE overlay showing score distributions.
- A Scatter Plot looking at individual student scores by department.
- A Line Chart displaying overall student score trends.

---

## Key Findings & Insights

1. **Department Trends:** Students in ECE secured the highest average score (~90.0), followed by CS (~81.5) and ME (~65.0).
2. **Statistical Proof:** T-test results confirmed that performance variations across groups are statistically significant ($p < 0.05$) and not just random noise.
3. **Data Cleaning:** Replacing missing values with the mean score worked cleanly without skewing the overall dataset balance.

---

## Conclusion & Repository Setup

All six required sections of the assessment are fully completed, verified, and pushed to my GitHub repository. The repository includes a configured `.gitignore` file to skip unnecessary cache and system files, clear markdown documentation in the notebook, and a well-structured `README.md`.

---

**Submitted by:** Shivam Kumar

---

**Support**

⭐ **If you found this project helpful, please give this repository a star!**
