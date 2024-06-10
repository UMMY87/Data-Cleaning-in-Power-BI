# Data Cleaning in Power BI
Certainly! Here is the README file for the data cleaning process in Power BI:

---

## Data Cleaning Process in Power BI

This guide provides a step-by-step process for cleaning and standardizing data in Power BI. Follow these instructions to ensure your data is accurate and well-formatted.

## Steps

### 1. Load Data into Power BI

1. Open Power BI Desktop.
2. Go to `Home` > `Get Data` and select your data source.
3. Load the data into Power BI.

### 2. AutoFit Columns

1. Right-click on the table name in the Fields pane.
2. Select `Edit Query` to open the Power Query Editor.
3. In the Query Editor, select each column and click the double-headed arrow at the top-right of the column header to auto-fit the column width.

### 3. Remove Duplicates

1. In the Power Query Editor, select the table.
2. Highlight the columns to check for duplicates.
3. Click `Remove Rows` -> `Remove Duplicates` in the Home tab.

### 4. Remove Blank Rows

1. In the Power Query Editor, select the table.
2. Click `Remove Rows` > `Remove Blank Rows` in the Home tab.

### 5. Standardize the "President" Column

1. In the Power Query Editor, right-click on the `president` column.
2. Select `Transform` > `Capitalize Each Word`.
3. Rename the column to "President".

### 6. Correct Typing Errors

1. In the Power Query Editor, select the `party` column.
2. Use the `Replace Values` function in the Transform tab to correct errors:
   - Replace “republicans” with “Republican”.
   - Replace “Whig   April 4, 1841  â€“  September 13, 1841” with “Whig”.
   - Replace “Demorcatic” with “Democratic”.
3. Rename the column to "Party".

### 7. Remove Additional Spaces in "Vice" Column

1. In the Power Query Editor, right-click on the `vice` column.
2. Select `Transform` > `Trim`.
3. Rename the column to "Vice".

### 8. Format Currency Column

1. In the Power Query Editor, right-click on the `salary` column.
2. Select `Data Type` > `Whole Number`.
3. Rename the column to "Salary".

### 9. Format Date Columns

1. In the Power Query Editor, right-click on the `date updated` column.
2. Select `Data Type` > `Date`.
3. Rename the column to "Date Updated".
4. In the Power Query Editor, right-click on the `date created` column.
5. Select `Data Type` > `Date`.
6. Rename the column to "Date Created".

### 10. Trim Data

1. Remove all unnecessary columns such as `Column1` and `prior`.

### 11. Load Data Back into Power BI

1. Click `Close & Apply` in the Power Query Editor to load the cleaned data back into Power BI.

## Conclusion

By following these steps, you will ensure that your data in Power BI is clean, standardized, and error-free. This process helps maintain data integrity and enhances the quality of your reports and analyses.

---

Feel free to modify and extend this README file as needed for your specific use case.
