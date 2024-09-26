## Overview

Solution to Function Programming Exercise Advanced with functionalities represented as SUT of UFCFVQ-15-M Reflective Report. This report details my learning experience and difficulties that I came across while doing two programming activities which are based on data analysis, function definitions in Python.

## Contents

`Task1/`: Contains the code for Programming Task 1 that involves defining functions to read CSV data and compute the Kendall Tau Rank Correlation Coefficient excluding external libraries.

- `Task2/`: Source code for Programming Task 2 (data preprocessing, outlier detection and elimination and hypothesis testing – Pearson correlation coefficient).

`notebooks/`: Jupyter notebooks used on the development of both tasks.

- `README. js`: Repo DescriptionREADME.

- `Reflective_Report. pdf: Comprehensive reflection on the constraints, successes and learnings of each coding task

## Installation

Python 3 is required to install from this. x installed on your machine. It was done using only Python built-in functionalities, so no other external libraries are necessary as it is course required.

1. Clone the repository:

```bash

git clone

cd

```

2. Go through the detailed solutions and analysis by opening up Jupyter notebooks from `notebooks/` directory.

## Usage

Task 1:-Defining Function

The `Task1/` directory pertains to the code for defining custom functions for dealing with data reading and processing (without making use of any external library). The main functions are:

`read_csv()`: This function is used to read CSV data from a file, and return it as the list of lists.

• kendall_tau_rank_correlation(): calculated the Kendall Tau Rank Correlation Coefficient.

Task 2: Data Preprocessing and Hypothesis Testing

Under the directory `Task2/` you will find scripts for DataSetCleaner, OutlierDetector and HypothesisTester respectively. The key scripts are:

- `data_preprocessing. py`: This file loads the data and then cleans & remove outliers from it using IQR.

- `hypothesis_testing. py: This code is used to find out the Pearson Correlation Coefficient and its associated p-value for hypothesis testing..

## Learning Outcomes

I have gained insight into:

1. Function Definitions: I spent a lot of time developing the right way to write a function and make it callable without being dependent on some other external library.

2. Data Preprocess: This contains the skills to handle and clean data particularly as detecting and removing outliers.

3. **STATISTICAL TESTING**: Used various statistical methods to test hypotheses and make sense of the results.

## Challenges and Solutions

- **Defining Functions**: When I first set out to define functions I struggled with this, but eventually got the hang of by paying closer attention in class and using outside resources.

Data Cleaning: faced problems with our outlier detection was fixed by doing some basic visualization to plot the distribution followed by IQR method.

- **Hypothesis Testing**: Haskell had trouble translating hypothesis testing from R to Python, but found a solution using the Pearson correlation coefficient.

## References

In the beginning (my week 11 working Jupyter notebook to practice the data science process)

Kendall rank correlation coefficient.wikipedia

- [Python Tutorial w3schools Course [**(HERE)**](https://www.w3schools.com/)

DataCamp Learn - python courses[**(Here)**](http://www.datacamp.com/)

---
