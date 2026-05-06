# PREDICTIVE-ANALYSIS-USING-MACHINE-LEARNING
COMPANY:CODTECH IT SOLUTIONS

NAME: Nandini Shankar Waghmare

INTERN ID:CTIS3494

DOMAIN:Data Analytics

DURATION:16 Weeks

MENTOR:NEELA SANTOSH

q1:
First, the data is loaded from a CSV file. Then, a few rows are shown using .head() to understand the data.
Next, the code finds the average salary for each country using groupby and mean. The result is shown using .compute().
After that, the data is filtered to show employees with salary more than 100000, and a few records are displayed.
Overall, the file shows how to load, check, calculate, and filter large data in a simple way.

q2:
First, the Dask library is imported. Then, the dataset is loaded from a CSV file using `dd.read_csv()`. This is useful because the dataset is large, and Dask can handle it easily without loading all data at once.
After loading the data, the first few rows are displayed using the `.head()` function. This helps to understand what the data looks like and what columns are present.
Next, the file performs some simple data analysis. It groups the data by the `country` column and calculates the average salary for each country using `groupby()` and `mean()`. The result is then shown using `.compute()`.
Then, the file filters the data to find employees who have a salary greater than 100000. This helps to identify high-salary employees. The first few rows of this filtered data are displayed.
Overall, this file shows simple steps like loading data, checking it, doing calculations, and filtering useful information. It also shows how large data can be handled easily using Dask instead of normal tools like Pandas.
