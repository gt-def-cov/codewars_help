# codewars_help

URL: https://www.codewars.com/kata/580d08b5c049aef8f900007c/train/sql

below doesn't answer the kata. i am just trying an MRE to see if I can cast the column, but it doesnt' work. 'test' is still in scientific notation
SELECT
  customer_id,
  amount,
  CAST(amount AS NUMERIC(18, 2)) AS test
FROM payment;
