# VEDA AI & ML Internship — Task 20: Sort Dataset Using Pandas

## 📌 Project Overview

This project demonstrates how to sort a dataset using Python and Pandas. It covers sorting numerical and categorical columns in ascending and descending order, sorting by multiple columns, and resetting DataFrame indices.

## 🎯 Objective

To understand how dataset sorting helps organize data, compare values, and perform effective data analysis.

## 🛠️ Tools and Technologies

* **Programming Language:** Python
* **Library:** Pandas
* **Environment:** Jupyter Notebook
* **Dataset:** Employee Dataset

## 📂 Project Structure

```text
VEDA-Task-20-Sort-Dataset/
│
├── VEDA_Task_20_Sort_Dataset.ipynb
└── README.md
```

## 📊 Dataset Description

The project uses a sample employee dataset with the following columns:

| Column      | Description                    |
| ----------- | ------------------------------ |
| Employee_ID | Employee identification number |
| Name        | Employee name                  |
| Department  | Employee department            |
| Age         | Employee age                   |
| Salary      | Employee salary                |

## 💻 Tasks Performed

### 1. Ascending Sorting

Sorted employee salaries from lowest to highest using `sort_values()`.

### 2. Descending Sorting

Sorted employee salaries from highest to lowest using `ascending=False`.

### 3. Categorical Sorting

Sorted employee names alphabetically and departments by category.

### 4. Multiple-Column Sorting

Sorted employees by department in ascending order and salary in descending order within each department.

### 5. Numerical Sorting

Sorted employees based on age and employee ID.

### 6. Index Resetting

Used `reset_index(drop=True)` to generate a new sequential index after sorting.

### 7. Identifying Top Salaries

Used sorting and `head()` to identify the three highest-paid employees.

## 🧠 Key Concepts Learned

* Pandas DataFrames
* `sort_values()`
* Ascending and descending order
* Sorting multiple columns
* Boolean sorting parameters
* `reset_index()`
* `head()` for selecting top rows

## ▶️ How to Run

1. Clone or download this repository.

2. Install Python and Jupyter Notebook.

3. Install Pandas:

   ```bash
   pip install pandas
   ```

4. Open Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

5. Open `VEDA_Task_20_Sort_Dataset.ipynb`.

6. Execute the cells sequentially to view the results.

## 🎤 Interview Questions

**1. How do you sort a DataFrame?**

Use `df.sort_values(by="Salary")`.

**2. What does `ascending=False` do?**

It sorts values in descending order.

**3. Can a DataFrame be sorted by multiple columns?**

Yes. Pass a list of column names to the `by` parameter.

**4. Does `sort_values()` modify the original DataFrame?**

By default, it returns a sorted DataFrame without modifying the original.

## ✅ Outcome

Successfully demonstrated dataset sorting using Pandas, including ascending order, descending order, categorical sorting, multiple-column sorting, and index resetting.

## 👨‍💻 Author

**Divakar R**
AI & ML Intern — VEDA

---

*Part of my VEDA AI & ML Internship task series.*
