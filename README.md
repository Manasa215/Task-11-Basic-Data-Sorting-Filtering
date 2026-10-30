# Task 11 – Basic Data Sorting & Filtering
**Program:** HI T – Data Analytics Track | **Level:** 1 | **Day:** 11

## Objective
Practice sorting and filtering a dataset to answer simple business questions while preserving the original data.

## Dataset
This submission uses a **20-row illustrative retail/superstore-style sample dataset created for practice**. It is not company data and is not presented as a downloaded Superstore dataset.

## Workbook contents
- `Raw_Data`: original sample records, kept unchanged.
- `Sorted_Data`: same records sorted by Sales from highest to lowest.
- `Filtered_Example`: records matching both conditions: Category = Technology AND Region = West.
- `Business_Answers`: five business questions and their answers.
- `Region_Summary`: total sales by region.

## Sorting and filtering performed
1. Sorted Sales in descending order to identify the largest orders.
2. Applied multiple filters together: Technology category and West region.
3. Kept the raw data in a separate worksheet without changing or deleting records.

## Five business questions and answers
1. **Which region has the highest total sales?** West – $4,228.00.
2. **Which category has the highest total sales?** Technology – $5,244.00.
3. **Which product has the highest total sales?** Smartphone – $4,794.00.
4. **Which orders have sales above $500?** ORD-1001, ORD-1006, ORD-1011, ORD-1013 and ORD-1016.
5. **How many orders were placed by Consumer customers?** 8 orders.

## Key findings
- West is the highest-sales region in this sample.
- Technology is the highest-sales category.
- Smartphones contribute the largest product-level sales total.
- Sorting and filtering make it easier to locate high-value orders and focus on a selected region/category combination.

## Interview questions
**Q1. When would you use filtering instead of deleting rows?**  
Use filtering when you want to temporarily view only records that meet specific conditions while keeping all original records available. Filtering is reversible; deleting rows removes data from the worksheet.

**Q2. Why should raw data be preserved?**  
Raw data should be preserved as a reliable original copy. It supports verification, repeat analysis, error checking and recovery if changes are made incorrectly. Analysis should be performed on a separate copy or worksheet.

## How to reproduce in Excel or Google Sheets
1. Open `Raw_Data`.
2. Select the dataset and use **Data → Sort** to sort Sales from Largest to Smallest.
3. Use the filter arrows in the header row.
4. Select Category = Technology and Region = West to apply multiple filters.
5. Clear the filters to show all records again.
6. Compare the results with `Business_Answers` and `Region_Summary`.

## Conclusion
This task demonstrates basic data exploration using sorting, single-condition filtering and multiple filters. Preserving the raw worksheet ensures the original records remain available for future analysis.
