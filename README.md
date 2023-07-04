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
```console
    HAVING <conditions>
```

- Extract a substring. 1-based indexing is followed in MySQL
```console
    SUBSTR(<string>,<beginning_index>,<number_of_characters_to_be_extracted>)
    SUBSTR(<string>,<beginning_index>)              
```

- Concatenate strings and varchars
```console
    CONCAT(<first_substring>,<second_substring>)
```

- Change to upper case
```console 
    UPPER(<string>)
```

- Change to lower case
```console
    LOWER(<string>)
```

- Check a value against multiple rows from a subquery
```console
    IN(<conditions>)
```

- Switch-Case Statement
```console
    CASE
    WHEN <conditions> THEN <actions>
    WHEN <conditions> THEN <actions>
    ELSE <actions>
    END
```

- If Statement
```console
    IF(<conditions>,<actions_if_conditions_satisfied>,<actions_in_else>)
```

- Alter and Rename the Column name
```console
    ALTER <table_name>
    RENAME COLUMN <old_column_name> <new_column_name>
```

- Update values in a Row, If the row is not present then nothing happens
```console 
    UPDATE <table_name>
    SET <column_no = value>, <column_no = value>
    WHERE <primary_key=row_id>
```

- Insert values in a Row
```console
    INSERT INTO <table_name>
    (
        <first_column_name>, <second_column_name>

    )
    VALUES 
    (
        <first_value>, <second_value>
    )
```

- Replace values in a Row, If the row is not present, then a new row is created. Replace = Insert+Update
```console
    REPLACE INTO <table_name>
    (
        <first_column_name>, <second_column_name>

    )
    VALUES 
    (
        <first_value>, <second_value>
    )
```

- Rename the Table
```console
    ALTER TABLE <old_table_name> 
    RENAME TO <new_table_name>
```