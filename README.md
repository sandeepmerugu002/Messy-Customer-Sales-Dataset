Messy Customer Sales DatasetCleaning a Messy Customer Sales Dataset Using Power Query

Over the past few days, I completed a hands-on data cleaning project using Microsoft Excel Power Query and Power BI Power Query.

The dataset was named messy_customer_sales_data and contained several common data quality issues found in real-world business data.

During this project, I cleaned and standardized the dataset step by step instead of trying to fix everything at once. This approach helped me understand not only the Power Query features but also the reasoning behind each cleaning decision.

Data quality issues solved
Removed duplicate Customer IDs while preserving valid records.
Standardized customer names by removing prefixes such as Mr., Mrs., Ms., and Dr.
Cleaned the Gender column by converting different formats (M, m, MALE, Female, etc.) into consistent values.
Fixed the Age column by removing extra text, correcting negative values, handling invalid values, and replacing missing ages using the median.
Standardized City names using Trim and Capitalize Each Word.
Learned how to correctly convert CSV date columns using Change Type with Locale in Power BI.
Understood when missing values should be kept because they have business meaning, such as Last Purchase Date and Feedback Score.
Key lessons learned

This project taught me that data cleaning is not only about removing errors. It is about understanding the business context before making changes.

For example:

Some missing values should be filled.
Some missing values should remain as null because they provide useful business information.
CSV files and Excel files behave differently when importing date columns.
Choosing the simplest and most maintainable Power Query transformation is often the best solution.
Tools Used
Microsoft Excel 2021
Power Query
Power BI Desktop
CSV and Excel datasets

This project strengthened my understanding of data cleaning and prepared me for creating reliable dashboards in Power BI.
