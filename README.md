# PFDA-Project
Programming for Data Analytics - ATU - Project

Data Source
https://www.met.ie/climate/available-data/historical-data

Data clean:
https://pandas.pydata.org/docs/reference/api/pandas.read_csv.html

I manage to separate the headers using a sep by "," , and the most important thing on_bad_lines = 'skip' since my code wasn't working because there is one line with more columns that the quantity of headers I have in my data.

Pandas:
https://pandas.pydata.org/docs/reference/api/pandas.to_numeric.html
errors = 'coerce' invalid parsing will be set as NaN.