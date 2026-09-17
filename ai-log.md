# AI Log

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
