# NumPy-Hands-on-Practice
Beginner NumPy practice covering arrays, dimensions, data types, element-wise operations and a weather temperature analysis mini-project.


## Overview

This repository contains my hands-on practice with NumPy as part of my Python learning journey with SmartBizCrux.

The exercises focus on moving from basic Python lists to NumPy arrays and using NumPy for numerical computing and simple data analysis.

## Learning Objectives

Through these exercises, I practiced how to:

- Import NumPy using the conventional alias "np"
- Create NumPy arrays from Python lists
- Identify 1D and 2D arrays
- Understand vectors and matrices
- Inspect array data types using "dtype"
- Compare Python list behavior with NumPy array behavior
- Perform element-wise numerical operations
- Compare numerical data across arrays
- Apply NumPy to a simple weather data analysis problem

## Hands-On Activities

1. Meet Your First NumPy Arrays

I converted temperature data from a Python list into a NumPy array and investigated its data type and dimensions.

I also created a 2D weather dataset and identified its structure as a matrix.

2. Python Lists vs NumPy Arrays

I compared how Python lists and NumPy arrays behave when performing addition.

The exercise demonstrated that:

- Python list + list performs concatenation.
- NumPy array + array performs element-wise addition.

I also practiced element-wise addition and subtraction using five days of sales data.

3. Weather Temperature Analysis

I used NumPy to analyse temperature data from a weather-monitoring scenario.

The analysis included:

- Creating and inspecting temperature arrays
- Identifying array dimensions and data type
- Calculating temperature differences from target values
- Increasing temperatures by a specified amount
- Identifying the highest recorded temperatures
- Comparing temperatures between Lagos, Abuja, and Ibadan

## Key Learning

One of the major lessons from this practice was that NumPy allows numerical operations to be performed efficiently across arrays without manually processing each value.

This makes numerical data easier to organize, calculate, and analyse as the amount of data increases.

## MINI PROJECT IN DETAILS

## Introduction

This Analyzed a week of temperature readings: computed the difference from a daily target, simulated a uniform +2° C increase, and answered analyst questions on which day peaked and which days exceeded target. The challenge extended this to three locations (Lagos, Abuja, Ibadan), finding the daily maximum across locations and applying a uniform +1°C adjustment.
Raw temperature readings from three locations are converted into NumPy arrays and compared against each other and a daily target. The exercises build up from single arrays to a multi-location comparison, using element-wise operations instead of loops.

## Findings

1. Lagos recorded the highest temperature for the first three days, while Abuja recorded the highest for the last two.
2. Lagos was warmer than Abuja on Days 1–3, by 2.5°C, 1.0°C, and 1.0°C respectively.
3. Abuja overtook Lagos on Days 4 and 5, by 2.0°C and 1.0°C respectively.
4. NumPy applied calculations (uniform increase, cross-location comparison) across every value at once, with no manual repetition.
5. This efficiency compounds as the dataset grows — the same operation scales without additional code.

## Conclusion

This project used NumPy to analyze temperature data from Lagos, Abuja, and Ibadan. Data was converted from Python lists to NumPy arrays, inspected, and compared using element-wise addition, subtraction, and maximum operations. Lagos recorded the highest temperatures in the first half of the week; Abuja took over for the second half.

# Snippets from the Mini Project

<img width="950" height="734" alt="Image" src="https://github.com/user-attachments/assets/9dbc8698-0a9b-4dbe-a994-b54a1b0681e0" />


<img width="981" height="750" alt="Image" src="https://github.com/user-attachments/assets/e2e7aef9-99c0-4743-89bf-5b4e1e6fb43a" />


<img width="979" height="731" alt="Image" src="https://github.com/user-attachments/assets/1ba21534-0cb2-4c48-9041-01733cfa86df" />


<img width="979" height="747" alt="Image" src="https://github.com/user-attachments/assets/7d5afed1-5966-44d6-8e6f-534d27201d4f" />

## Bonus Challenge

The bonus challenge tested my understanding of element-wise operations using:

x + y
x - y
x * y

I predicted the results before running the code and compared my predictions with Python's output.

## Tools

- Python
- NumPy
- Jupyter Notebook
- GitHub

## Learning Context

This project was completed as part of my Python/Data Analytics training with SmartBizCrux under the guidance of Coach Timothy.

## Author
Vivian Gomes - Geoscientist | Data Analyst
