📊 Student Feedback Ratings — Analysis Project (Internship Task)

This repository contains my analysis for the Future Interns Data Science & Analytics Task.
The aim of this task was to examine a dataset of numeric student feedback ratings and extract meaningful insights using Python.

The dataset includes only numbers (1–10 scale) rather than written comments, so the project focuses entirely on quantitative trends, averages, patterns, and correlations.

📁 Dataset Overview

The file student_feedback.csv includes over 1000 responses, with columns covering several aspects of teaching and course experience, such as:

Knowledge of the subject

Clarity in explaining concepts

Use of presentations

Assignment difficulty

Willingness to solve doubts

Course structure

Support provided to students

Course recommendation

Each column represents a rating given by a student.

🔧 Tools & Libraries Used

Python (Google Colab)

pandas — loading & cleaning data

matplotlib / seaborn — visualisation

wordcloud — installed, but not used due to no text-based feedback

🔍 Project Workflow
1. Data Loading & Cleaning

Imported the CSV file

Dropped unnecessary index columns

Verified shape, missing values, and column consistency

2. Exploratory Data Analysis

Summary statistics for each metric

Comparing averages across categories

Checking variability in different feedback areas

3. Visual Insights

Generated several plots to understand the distribution and relationships:

Histograms for each rating

Bar plots of mean scores

A correlation heatmap to observe how metrics relate

4. Findings from the Data

A few noticeable patterns:

Most students rated subject knowledge and explanation clarity highly

Assignment difficulty varied widely, showing mixed student experience

Course structure and support had moderate but inconsistent ratings

Strong correlation observed between clear explanations and better ratings overall

💡 What the Insights Suggest

More consistency is needed in assignment difficulty

Students appreciate good explanations and interactive presentations

Extra academic support could help improve lower-rated areas

📝 Conclusion

This project demonstrates skills in:

Data cleaning

Analytical thinking

Visual interpretation

Working with real feedback datasets

Presenting insights in a simple, structured format

It highlights how numeric feedback alone can be used to evaluate teaching quality and identify improvement areas.
