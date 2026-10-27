# 📊 Survey Feedback Analyzer

### Python-Based Feedback Analysis and Insight Extraction

A Python project that analyzes survey feedback, cleans textual data, evaluates customer ratings, and extracts meaningful insights using fundamental Python programming concepts and Pandas.

---

## 📌 Project Overview

The **Survey Feedback Analyzer** is a data analysis project designed to process written survey responses and numerical ratings. It transforms raw feedback into structured, readable data and generates useful summaries to understand customer experiences and identify frequently mentioned words.

The project demonstrates how Python can be used for basic text processing, data cleaning, and exploratory analysis.

## 🎯 Project Objectives

- Organize survey responses using a dictionary of lists.
- Collect additional feedback interactively from users.
- Clean text by removing punctuation, extra spaces, and inconsistent capitalization.
- Count feedback entries containing specific keywords.
- Calculate the average rating across all responses.
- Identify the longest feedback comment.
- Extract unique words from the collected feedback.
- Sort feedback entries by rating to support comparison.

## 🛠️ Technologies & Tools

| Technology | Purpose |
|---|---|
| Python | Core programming and analysis |
| Jupyter Notebook | Interactive development and execution |
| Pandas | Tabular data representation and analysis |
| Regular Expressions | Text cleaning and whitespace handling |

## ⚙️ Key Features

**1. Feedback Management**

Stores initial survey responses and allows users to enter additional names, comments, and ratings.

**2. Text Preprocessing**

Standardizes feedback by removing specified punctuation, eliminating unnecessary spaces, and converting text to lowercase.

**3. Keyword Analysis**

Counts how many feedback entries contain selected words, such as `good`, `poor`, and `excellent`.

**4. Rating Analysis**

Calculates the average rating and organizes feedback from highest to lowest rating.

**5. Summary Insights**

Identifies the longest comment and generates a sorted collection of unique words.

**6. Tabular Data Presentation**

Displays feedback records and analytical summaries in structured tables using Pandas DataFrames.

## 🔄 Project Workflow

1. Initialize the survey feedback dataset.
2. Collect additional feedback from users.
3. Clean and standardize textual responses.
4. Analyze keyword occurrences.
5. Calculate rating statistics and identify the longest comment.
6. Extract unique words and optionally sort feedback by rating.

## 📂 Project Structure

```text
Survey-Feedback-Analyzer/
│
├── survey-feedback-analyzer.ipynb
└── README.md
```

## 🚀 Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook
- Pandas

### Installation

Install Pandas if it is not already available:

```bash
pip install pandas
```

### Run the Project

1. Clone or download this repository.
2. Open the project notebook in Jupyter Notebook.
3. Execute the cells sequentially from top to bottom.
4. Enter additional feedback when prompted.
5. Review the cleaned dataset, keyword counts, ratings, and summary insights.

## 📈 Expected Outputs

- Cleaned survey feedback displayed in a table.
- Keyword frequency summary for selected words.
- Average rating of all feedback entries.
- Longest feedback comment with its word count.
- List of unique words used across the feedback.
- Feedback records sorted by rating.

## 📚 Python Concepts Demonstrated

- Variables and Data Types
- Lists and Dictionaries
- Loops and Conditional Statements
- User-Defined Functions
- String Manipulation
- List Comprehensions
- Sets and Sorting
- Regular Expressions
- Pandas DataFrames
- Basic Data Analysis

## 💡 Learning Outcomes

This project provides practical experience in organizing data, processing text, applying conditional logic, defining reusable functions, and summarizing information. It also demonstrates the use of Python tools to convert raw survey responses into structured data suitable for further analysis.

## 👨‍💻 Author

**Roshan**

BCA Graduate | Aspiring Data Analyst

Interested in Python, Data Analytics, Business Intelligence, and Machine Learning.

---

*Developed as part of Python Fundamentals coursework to practice programming, data cleaning, and feedback analysis.*
