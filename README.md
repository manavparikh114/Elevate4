SELECT SUM(numeric_column) AS total_value
FROM table_name;
SELECT COUNT(*) AS total_records
FROM table_name;
SELECT AVG(numeric_column) AS average_value
FROM table_name;
SELECT category_column, SUM(numeric_column) AS total_per_category
FROM table_name
GROUP BY category_column;
SELECT category_column, COUNT(*) AS count_per_category
FROM table_name
GROUP BY category_column
HAVING COUNT(*) > 10;
