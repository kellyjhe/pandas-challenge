# pandas-challenge

<b>Module 4 Challenge</b></p>
In this assignment, you’ll create and manipulate Pandas DataFrames to analyze school and standardized test data.<p><p>
<b>Background</b><p>
You are the new Chief Data Scientist for your city's school district. In this capacity, you'll be helping the school board and mayor make strategic decisions regarding future school budgets and priorities.<p>

As a first task, you've been asked to analyze the district-wide standardized test results. You'll be given access to every student's math and reading scores, as well as various information on the schools they attend. Your task is to aggregate the data to showcase obvious trends in school performance.<p>

<b>Code Help</b></p>
I used Xpert for help with code on calculating average test scores per school, in Cell 14.
per_school_math = school_df.groupby("school_name")["math_score"].mean()
per_school_reading = school_df.groupby("school_name")["reading_score"].mean()

Code was also used from the sample solution, PyCitySchools_starter.ipynb. These include Cells 7, 9, 10, 11, 17, 18, 19, 22, 23, 24, 25,c26, 27, 29, 31, 33.
