# Math2

A Python-based data analysis project focused on student exam performance using data visualization, statistical insights, and condition-based analysis techniques.

## Overview

This project analyzes a student examination dataset to identify patterns between study habits, attendance, group discussions, and exam performance. The notebook demonstrates practical usage of Python libraries for data preprocessing, exploratory data analysis (EDA), and visualization.

The analysis is performed in a Jupyter Notebook environment and includes multiple visual and logical representations of the dataset.

## Features

* Data loading and preprocessing using Pandas
* Exploratory Data Analysis (EDA)
* Statistical summaries and condition-based filtering
* Data visualization with Matplotlib and Seaborn
* Venn diagram analysis for overlapping student conditions
* Performance comparison based on attendance and study hours

## Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Matplotlib-Venn

## Dataset Information

The dataset contains student-related academic attributes such as:

| Column Name           | Description                        |
| --------------------- | ---------------------------------- |
| `study_hours`         | Number of study hours              |
| `attendance`          | Attendance percentage              |
| `group_discussion`    | Participation in group discussions |
| `previous_test_score` | Previous test marks                |
| `final_exam_pass`     | Final exam result                  |

## Project Structure

```text
Math2/
│
├── Math2.ipynb                 # Main notebook file
├── student_exam_dataset.csv   # Dataset used for analysis
└── README.md                  # Project documentation
```


git clone https://github.com/Mant-0957/Math2.git


Execute the notebook cells sequentially to:

* Load the dataset
* Analyze student performance
* Generate charts and visualizations
* Perform logical condition analysis
* Display Venn diagrams for overlapping conditions

## Example Analysis

The notebook includes:

* Attendance vs Exam Performance analysis
* Study hours distribution
* Correlation insights
* Conditional filtering using Boolean logic
* Visualization of overlapping student conditions using Venn diagrams

## Sample Venn Diagram Logic

```python
A = df["study_hours"] > 10
B = df["attendance"] > 80

only_A = sum(A & ~B)
only_B = sum(B & ~A)
both_AB = sum(A & B)
```

## Learning Outcomes

This project demonstrates:

* Practical data analysis workflows
* Python visualization techniques
* Boolean condition handling in datasets
* Basic statistical interpretation
* Exploratory data analysis using real-world academic data

## Future Improvements

Potential enhancements include:

* Machine learning-based prediction models
* Interactive dashboards
* Advanced statistical analysis
* Automated report generation
* Additional visualization techniques

## Author

Developed by Mant-0957.

[Math2 Repository](https://github.com/Mant-0957/Math2?utm_source=chatgpt.com)
