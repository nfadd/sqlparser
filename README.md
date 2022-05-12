# sqlparser
This is a basic SQL parser using Lark in Python

My parser deals with a few common keywords in SQL. Below is a list of the keywords that can be used:
- AND
- ASC
- BETWEEN
- BY
- DESC
- FROM
- MAX
- MIN
- ORDER
- SELECT
- WHERE

It is important to note that while you can use different options like WHERE and ORDER BY, the program will work only when one is used at a time. The program allows you to select all (\*\) or specific columns if you choose. 

# Data Tables
There are two built-in data tables, "People" and "Sports". Below is an example of how they are structured.

People
first_name | last_name | age | city | day | month | year | alive
--- | --- | --- | --- | --- | --- | --- | ---
Elvis | Presley | 42 | Memphis | 8 | 1 | 1935 | no
Elton | John | 75 | Pinner | 25 | 3 | 1947 | yes
Ariana | Grande | 36 | Boca Raton | 6 | 6 | 1993 | yes
Katy | Perry | 37 | Santa Barbara | 25 | 10 | 1984 | yes
Perry | Lively | 34 | Los Angeles | 25 | 8 | 1987 | yes

Sports
team | city | standing | year_founded
--- | --- | --- | ---
Arsenal | London | 4 | 1886
Manchester United | Manchester | 6 | 1878
Brentford | Brentford | 12 | 1889
Liverpool | Liverpool | 2 | 1892


# Try It Out Yourself
To run the program, type in the command `python3 sqlparser.py`. You will be prompted to either select from one of the 8 built in examples or create your own SQL query.
