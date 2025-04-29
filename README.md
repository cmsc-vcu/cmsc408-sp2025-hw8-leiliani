# Welcome to Homework 8 - SQL Funhouse!

- [Welcome to Homework 8 - SQL Funhouse!](#welcome-to-homework-8---sql-funhouse)
  - [Overview](#overview)
  - [Setup Instructions](#setup-instructions)
  - [Files and Folders](#files-and-folders)

## Overview

For this assignment, I am working as a data analyst for the World Bank, using the World Development Indicators (WDI) database. The datasets are large, so I need to be careful with how I manage interim tables to ensure efficient analysis.

The World Bank is an international organization focused on reducing poverty and promoting economic development through financial support, grants, and research.

The WDI is a major database maintained by the World Bank, containing key economic and social development data. I used it to perform analyses on global development trends and challenges.

The goal of this project was to explore and manipulate the World Bank WDI (World Development Indicators) dataset using SQL. By querying, cleaning, updating, and organizing country data, we practiced fundamental SQL skills like SELECT, WHERE, GROUP BY, ORDER BY, AGGREGATE FUNCTIONS, CASE statements, and subqueries.

[Here is a link](https://virginiacommonwealth.instructure.com/courses/113813/assignments/1072347) to Homework 8 in Canvas.


## Setup Instructions

You will need poetry, Pyenv, VSCode, and Quarto.

- Clone the GitHub repo
- poetry install
- poetry shell
- cd reports
- quarto render report.qmd
- open report.html

OR

- Open the reports folder
- Access the report.html file [here](reports/report.html)
- Download the report.html file and open in browser

## Files and Folders

- *./reports* - contains the modified Homework 8 QMD file, rendered HTML file, and _quarto.yml file.
  - the [_quarto.yml](reports/_quarto.yml) file includes the author and date information and applies that to the rendered html file  
- *./source-data* — contains the Makefile and Python code used to populate the MySQL server with data for Homework 8.
  - running `make all` downloads source data in ZIP format from the World Bank, unzips required CSV files, and loads them into MySQL using Pandas and SQLAlchemy.