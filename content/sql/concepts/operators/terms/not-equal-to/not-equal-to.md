---
Title: 'Not Equal To Operator'
Description: 'The Not Equal To operator in SQL is used to compare two values and returns true if they are not equal.'
Subjects:
  - 'Computer Science'
  - 'Data Science'
Tags:
  - 'SQL'
  - 'Operators'
CatalogContent:
  - 'learn-sql'
  - 'paths/data-science'
---

In SQL, the **Not Equal To** operator is used to compare two values. It returns true if the values are not equal and false if they are equal. The operator can be represented in two ways: `<>` or `!=`.

## Syntax

```sql
-- Using the <> operator
SELECT column1, column2, ...
FROM table_name
WHERE column_name <> value;

-- Using the != operator
SELECT column1, column2, ...
FROM table_name
WHERE column_name != value;
```

## Example

The given query will select all employees who are not in the 'Sales' department using the `<>` operator.

```sql
SELECT *
FROM employees
WHERE department <> 'Sales';
```