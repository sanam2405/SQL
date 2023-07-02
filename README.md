# SQL
Learning Structured Query Language


## Methods

- Check if an expression returns NULL
```console
    IFNULL(<expression>,<alternate_value>)
```

- Limit the number of results printed on firing a given query
```console
    LIMIT <offset>,<values_taken>
```
- Find the difference between two dates
```console
    DATEDIFF(<first_date>,<second_date>)
```

- Match a Regular Expression or REGEX 
```console
    LIKE <regular_expression>
```
- Concatenate the results of a query into a single row
```console
    GROUP_CONCAT(<query_returning_multiple_row_values>)
```

- Find the unique or distinct values across all the rows of a column 
```console
    DISTINCT <column_name>
```

- Group multiple similar rows of a particular column
```console
    GROUP BY <column_name>
```

- Order the output by ascending or descending order on firing a given query
```console
    ORDER BY <column_name> DESC 
```

- Specify conditions to query rows from a table 
```console
    WHERE <conditions>
```
- Specify conditions to query groups from a table, after GROUP BY has been applied 
``` console
    HAVING <conditions>
```