![logo_ironhack_blue 7](https://user-images.githubusercontent.com/23629340/40541063-a07a0a8a-601a-11e8-91b5-2f13e4e6b441.png)

# Lab | Introduction to R and Tidyverse

This exercise is designed to help you practice basic R programming and data manipulation using the `dplyr` package from the Tidyverse. Follow the instructions below and complete the tasks in your R environment.

## Setup

1. **Install and load the Tidyverse**: If you haven't already, install the `tidyverse` package and load it into your R session.

```r
install.packages("tidyverse")
library(tidyverse)
```

2. **Create a data frame:** Use the following code to create a sample data frame for this exercise.
```r
employees <- data.frame(
		  ID = 1:6,
		  Name = c("Alice", "Bob", "Charlie", "David", "Eve", "Frank"),
		  Age = c(25, 30, 35, 40, 45, 50),
		  Department = c("HR", "IT", "Finance", "IT", "HR", "Finance"),
		  Salary = c(50000, 60000, 70000, 80000, 55000, 75000)
		)
```

This data frame contains information about employees, including their ID, name, age, department, and salary.

## Tasks

### Task 1: Explore the Data
1. Print the employees data frame to the console.
2. Use the str() function to inspect the structure of the data frame.
3. Use the summary() function to get a summary of the data.


### Task 2: Basic Data Manipulation with dplyr

1. Filter rows: Create a new data frame that includes only employees who work in the "IT" department.
2. Select columns: Create a new data frame that includes only the Name and Salary columns.
3. Add a new column: Add a new column called Bonus that calculates a 10% bonus for each employee based on their salary.
4. Sort rows: Sort the employees data frame by Salary in descending order.
5. Summarize data: Calculate the average salary for each department.

## Optional Exercises

### Extra 1: Advanced Data Manipulation

1. Group and summarize: Group the data by Department and calculate the total salary expenditure for each department.
2. Filter and mutate: Create a new data frame that includes only employees older than 30 and adds a column called Experience that assumes each employee has Age - 25 years of experience.

### Extra 2: Challenge

1. Combine operations: Create a new data frame that includes employees from the "HR" department, adds a Bonus column (10% of salary), and sorts the data by Bonus in descending order.
2. Visualize data: Use ggplot2 to create a bar plot showing the total salary expenditure by department.

## Deliverables

- Submitted notebook (or file) with your responses to each of the exercises.

## Submission

- Upon completion, add your deliverables to git. 
- Then commit git and push your branch to the remote.
- Make a pull request and paste the PR link in the submission field in the Student Portal.

<br>

**Good luck!**