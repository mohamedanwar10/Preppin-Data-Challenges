# 2024 - Week 2: Unions, Aggregation, and Reshaping Data

## Challenge Description
This week's challenge involves unions, aggregation, and reshaping data. The input dataset is the output from Week 1.

### Requirements
1. Input the two CSV files.
2. Union the files together.
3. Convert the `Date` field to a quarter number and name this field `Quarter`.
4. Aggregate the data in the following ways:
   - Median price per Quarter, Flow Card?, and Class.
   - Minimum price per Quarter, Flow Card?, and Class.
   - Maximum price per Quarter, Flow Card?, and Class.
5. Create three separate flows, each containing one of the aggregated measures:
   - One for the minimum price.
   - One for the median price.
   - One for the maximum price.
6. Pivot the data to have a column per class for each quarter and whether the passenger had a Flow Card or not.
7. Union these flows back together.
8. Rename the columns:
   - Economy to First.
   - First Class to Economy.
   - Business Class to Premium.
   - Premium Economy to Business.
9. Output the data with the following fields:
   - Flow Card?
   - Quarter
   - Economy
   - Premium
   - Business
   - First

### Approach
- Used Power Query to union the two CSV files.
- Extracted the quarter from the `Date` field.
- Aggregated the data using median, minimum, and maximum prices.
- Pivoted the data to reshape it.
- Renamed the columns as required.

### Files
- **Input Data**:
  - `week1_output_1.csv`
  - `week1_output_2.csv`
- **Solution**:
  - `solution.pbix` (Power BI file with Power Query steps)
- **Output**:
  - `output.pbix` (Power BI file with Power Query steps)
