# SQL
Learning Structured Query Language


## Methods

- Check if an expression returns NULL
```mysql
    IFNULL(<expression>,<alternate_value>)
```

- Limit the number of results printed on firing a given query
```mysql
    LIMIT <offset>,<values_taken>
```
- Find the difference between two dates
```mysql
    DATEDIFF(<first_date,second_date>)
```

- Match a Regular Expression or REGEX 
```mysql
    LIKE <regular_expression>
```
- Concatenate the results of a query into a single row
```mysql
    GROUP_CONCAT
```

- Find the unique or distinct values across all the rows of a column 
```mysql
    DISTINCT
```

- Group multiple similar rows of a particular column
```mysql
    GROUP BY <column_name>
```

- Order the output by ascending or descending order on firing a given query
```mysql
    ORDER BY
```

- Specify conditions to query rows from a table 
```mysql
    WHERE <conditions>
```
- Specify conditions to query groups from a table, after GROUP BY has been applied 
``` mysql
    HAVING <conditions>
```