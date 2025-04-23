# 🎓 Student Performance Data Analysis Using Python

This project performs a detailed data analysis on a dataset of student exam scores to extract meaningful insights using fundamental Python tools and libraries.

## 📁 Dataset

- **File:** `student-mat.csv`
- **Source:** UCI Machine Learning Repository or provided by the instructor
- **Columns include:**
  - `G1`, `G2`, `G3` – grades for three terms (focus on `G3` as final grade)
  - `studytime` – weekly study hours
  - `sex` – gender (`M` for male, `F` for female)
  - Other supporting attributes

---

## 🧠 Objectives

- Learn data loading, cleaning, and exploration using **pandas**
- Perform basic statistical analysis using **NumPy**
- Create visualizations with **matplotlib** and **seaborn**
- Answer key analytical questions about student performance

---

## 📌 Tasks Performed

### 1. Data Loading
- Loaded the dataset using `pandas.read_csv()`
- Displayed first few rows using `.head()`

### 2. Data Exploration
- Checked for missing values with `.isnull().sum()`
- Displayed data types with `.dtypes`
- Found dataset size using `.shape`

### 3. Data Cleaning
- Removed missing values
- Removed duplicate rows

### 4. Data Analysis
- ✅ Calculated the **average final grade (G3)**
- ✅ Counted **students who scored above 15** in G3
- ✅ Found **correlation between study time and final grade**
- ✅ Determined **which gender has a higher average G3**

### 5. Data Visualization
- 📊 Histogram of final grades (G3)
- 📈 Scatter plot: study time vs G3
- 🧑‍🤝‍🧑 Bar chart comparing average G3 by gender

---

## 📷 Sample Visualizations

> Include images of your plots here using:
> ```
> ![Histogram](images/histogram.png)
> ![Scatter](images/scatter.png)
> ![Bar](images/bar.png)
> ```

---

## 🛠️ Technologies Used

- Python
- pandas
- numpy
- matplotlib
- seaborn
- Jupyter Notebook

---

## 📄 Project Structure

