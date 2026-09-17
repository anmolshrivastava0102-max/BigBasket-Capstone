# AI Log
## Prompt 1 — SQLite SQL Reporting

### R — Role
You are an SQL expert specializing in SQLite and business reporting.

### C — Context
I am working on the BigBasket Capstone database. It contains orders and products tables. The orders table contains order_id, customer_id, product_id, order_date, quantity, amount_inr, payment_mode and status. The products table contains product_id and category.

### T — Task
Write a SQLite SQL query for a monthly-by-category revenue report. The output must contain category, month, order_count, total_revenue and avg_revenue. Use only Delivered orders and group the results by category and month.

### C — Constraints
Use SQLite-compatible SQL only. Keep the query simple and suitable for my BigBasket Capstone database. Do not change the table structure or modify the source data.

### F — Format
Provide the SQL query in a code block and briefly explain what each part of the query does.

### Verification
I ran the suggested SQL query in my SQLite database and checked that the output contained the expected category-month rows and revenue values.
## Prompt 2 — Pandas Cleaning/Analysis Explanation

### R — Role
You are a Pandas and data-cleaning expert helping me understand my BigBasket sales analysis code.

### C — Context
I am cleaning the BigBasket orders data in Pandas. My analysis includes handling outliers and preparing the cleaned data for revenue analysis.

### T — Task
Explain how the Pandas outlier-cleaning logic works, especially how the IQR method and `.clip()` are used to cap extreme values.

### C — Constraints
Keep the explanation simple and focused on my BigBasket dataset. Do not change the overall analysis approach.

### F — Format
Explain the logic step by step and provide a clear Pandas example.

### Verification
I re-ran the suggested `.clip()` logic and manually checked previously identified outlier rows to verify that their values were capped at the calculated upper-fence value.
