# Adventure Works Data



## Data Cleaning and Preparation (in Excel):

- For 'Sales' Data:

![image](https://github.com/user-attachments/assets/85afb343-cc20-4d0a-8b77-7f635fcc0b7e)

Applied Filters:
Added filters to all column headers to enable efficient data sorting and filtering.

Handled Missing 'TransactionId' Values:
Removed rows with blank entries in the TransactionId column to ensure data completeness and integrity.

Ensured TransactionId Data Type Consistency:
Converted the TransactionId column to a numerical data type to facilitate accurate calculations and analysis.

Cleaned Non-Numeric 'SalesAmount' Values:
Manually identified and replaced any non-numeric entries within the 'SalesAmount' column to ensure data consistency and accuracy.

Replaced Missing with Zero:
Any blank or missing values were replaced with 0 to ensure these entries are included in the analysis and prevent data exclusion.

Results:

![image](https://github.com/user-attachments/assets/81383f8b-2781-4109-b2a9-ee2fad707148)
________________________
- For 'Inventory' Data:

![image](https://github.com/user-attachments/assets/7c47add7-0071-478c-b76b-41552df8e9ce)

Addressing Missing 'ProductName':
Applied a filter to the 'ProductName' column.
Removed rows with blank 'ProductName' entries to ensure the analysis includes only complete product records.

Handling Missing 'Category':
Selected the 'Category' column.
Initiated a manual review of missing entries within this column to prepare for evaluation and imputation.

Standardizing 'RestockingFrequency':
Selected the 'RestockingFrequency' column.
Used Find and Replace (CTRL + H) to standardize entries: "30 d" was replaced with "30 days", ensuring "Match entire cell contents" was selected for precise replacement.

Results:

![image](https://github.com/user-attachments/assets/bde2fb3c-ea10-4e80-bb7e-8959936556d6)
_____________________________________________

For 'Customer-Feedback' Data:

![image](https://github.com/user-attachments/assets/b8e80965-6fc7-48be-9fca-d32f2f34470e)

Addressing Missing 'FeedbackID':
Applied a filter to the 'FeedbackID' column.
Removed rows with blank 'FeedbackID' entries to ensure data completeness and reliability.

Dealing with Inconsistent 'FeedbackScore':
Set the 'FeedbackScore' column's data type to Number to ensure consistent numerical treatment.
Manually identified and corrected non-numeric values (e.g., "four-comma-seven" to "4.7") to maintain data integrity.

Correcting Invalid Dates in 'FeedbackDate':
Set the 'FeedbackDate' column's data type to Date and applied the mm/dd/yyyy custom format.
Manually identified and corrected non-date values (e.g., "five May 2023" to "05/05/2023") to ensure accurate date interpretation.

Results:

![image](https://github.com/user-attachments/assets/826f818e-a865-4156-aeca-c670f6f57c56)
________________________________




