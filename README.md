# pandas-challenge

![Education](https://github.com/kgregart/pandas-challenge/blob/main/Images/education.png)

## Background

As a new Chief Data Scientist for the city's school district, the school board and mayor make will need help making strategic decisions regarding future school budgets and priorities.

As a first task, analyze the district-wide standardized test results with access to every student's math and reading scores with various information on the schools they attend. Aggregate the data to showcase obvious trends in school performance.

## Instructions

Using Pandas and Jupyter Notebook, create a report that includes the following data. Your report must include a written description of at least two observable trends based on the data.

Hint: Check out the sample solution called PyCitySchools_starter.ipynb located in the .zip file to review the desired format for this assignment.

__District Summary__

Perform the necessary calculations and then create a high-level snapshot of the district's key metrics in a DataFrame.

Include the following:

- Total number of unique schools

- Total students

- Total budget

- Average math score

- Average reading score

- % passing math (the percentage of students who passed math)

- % passing reading (the percentage of students who passed reading)

- % overall passing (the percentage of students who passed math AND reading)

__School Summary__

Perform the necessary calculations and then create a DataFrame that summarizes key metrics about each school.

Include the following:

- School name

- School type

- Total students

- Total school budget

- Per student budget

- Average math score

- Average reading score

- % passing math (the percentage of students who passed math)

- % passing reading (the percentage of students who passed reading)

- % overall passing (the percentage of students who passed math AND reading)

__Highest-Performing Schools (by % Overall Passing)__
Sort the schools by % Overall Passing in descending order and display the top 5 rows.

Save the results in a DataFrame called "top_schools".

__Lowest-Performing Schools (by % Overall Passing)__
Sort the schools by % Overall Passing in ascending order and display the top 5 rows.

Save the results in a DataFrame called "bottom_schools".

__Math Scores by Grade__
Perform the necessary calculations to create a DataFrame that lists the average math score for students of each grade level (9th, 10th, 11th, 12th) at each school.

__Reading Scores by Grade__
Create a DataFrame that lists the average reading score for students of each grade level (9th, 10th, 11th, 12th) at each school.

__Scores by School Spending__
Create a table that breaks down school performance based on average spending ranges (per student).

Use the code provided below to create four bins with reasonable cutoff values to group school spending.
image of results

Use pd.cut to categorize spending based on the bins.

Use the following code to then calculate mean scores per spending range.

image of results

Use the scores above to create a DataFrame called spending_summary.

Include the following metrics in the table:

- Average math score

- Average reading score

- % passing math (the percentage of students who passed math)

- % passing reading (the percentage of students who passed reading)

- % overall passing (the percentage of students who passed math AND reading)

__Scores by School Size__

Use the following code to bin the per_school_summary.

image of results

Use pd.cut on the "Total Students" column of the per_school_summary DataFrame.

Create a DataFrame called size_summary that breaks down school performance based on school size (small, medium, or large).

__Scores by School Type__

Use the per_school_summary DataFrame from the previous step to create a new DataFrame called type_summary.

This new DataFrame should show school performance based on the "School Type".

