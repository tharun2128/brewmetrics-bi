# Copilot DAX Development Notes

## 1. Month-over-Month Sales Growth

### Copilot suggestion
Copilot suggested using DATEADD to compare current month sales with the previous month.

### My correction
I checked the formula against the Power BI date dimension and verified the Dim_Date[date] column was being used.

### Final result
The measure calculates month-over-month sales growth.

## 2. Running Total Sales

### Copilot suggestion
Copilot suggested using CALCULATE with a date filter to calculate cumulative sales.

### My correction
I checked the date context and used ALLSELECTED so the calculation responds to report selections.

### Final result
The measure calculates cumulative sales over the selected period.

## 3. Item Sales Rank

### Copilot suggestion
Copilot suggested using RANKX to rank items by sales.

### My correction
I checked the product field and verified that Dim_Product[item] was being ranked.

### Final result
Items are ranked from highest to lowest sales.

## 4. Average Sale Value

### Copilot suggestion
Copilot suggested calculating the average of sales_amount.

### My correction
I verified that Fact_Sales[sales_amount] was the correct field.

### Final result
The measure calculates the average transaction value.
