Survey Feedback Analyzer

A Python project for survey data processing, text cleaning, and feedback insights.

About the Project

Survey Feedback Analyzer is a Python-based project that processes customer feedback and ratings to generate meaningful summaries. It uses Python programming concepts and Pandas to organize survey data, standardize written responses, analyze keyword occurrences, and present results in structured tables.

The project focuses on converting raw feedback into clean, organized, and easy-to-understand information.

Project Highlights

Data Management: Stores survey responses using a dictionary of lists and supports additional user inputs.

Text Cleaning: Removes specified punctuation, normalizes whitespace, and converts feedback to lowercase.

Keyword Analysis: Counts feedback entries containing selected words such as good, poor, and excellent.

Rating Analysis: Calculates the average rating and sorts feedback from highest to lowest rating.

Feedback Insights: Identifies the longest comment and extracts unique words.

Data Presentation: Displays feedback and analytical results using Pandas DataFrames.

Tech Stack

Tool

Application

Python

Programming and analysis

Pandas

Structured data and tabular output

Jupyter Notebook

Development and execution

Regular Expressions

Text preprocessing

Workflow

Raw Survey Feedback
        ↓
Data Collection
        ↓
Text Cleaning
        ↓
Keyword Analysis
        ↓
Rating Analysis
        ↓
Summary & Insights

Repository Contents

File

Description

survey-feedback-analyzer.ipynb

Python notebook containing the implementation

README.md

Project documentation

Getting Started

Requirements

Python 3.x

Jupyter Notebook

Pandas

Setup

Install the required library:

pip install pandas

Open the notebook in Jupyter Notebook and execute the cells sequentially. Enter additional feedback when prompted to explore the analysis with new records.

Key Learning Outcomes

Through this project, I practiced:

Python lists, dictionaries, loops, and conditionals

Functions and string manipulation

Data cleaning and preprocessing

Sets, sorting, and list comprehensions

Pandas DataFrames and basic data analysis

Extracting insights from text-based feedback

Future Enhancements

Sentiment classification for positive, negative, and neutral feedback

Interactive feedback entry and validation

Visualizations for rating distributions

Exporting cleaned data and summary reports to CSV

Advanced text analysis using Natural Language Processing (NLP)
