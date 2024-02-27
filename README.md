# Overview
#### In this project, we aimed to clean the 'Raw file US Presidents' Excel dataset obtained from Kaggle. The dataset contains information about the Presidents of the United States, including:
###
* S.No.: Serial number.
* President: Name of the President.
*	Prior: The primary position or role held before becoming President.
*	Party: The political party affiliation.
*	Vice: The Vice President during their presidency.
*	Salary: The salary received during their presidency.
*	Date Updated: The last date the information was updated.
*	Date Created: The date the record was created.
The dataset contained various inconsistencies such as duplicate entries, inconsistent capitalization, irregular date formats, and redundant data. The following steps outline the process of cleaning the data using Excel functionalities.

### Steps Taken
###
**Step 1: Duplicate File Creation and Initial Inspection**
###
To ensure the safety of the original data, we first created a duplicate file to perform our cleaning operations. This duplicate file serves as a backup for the original dataset.
###
**Step 2: Checking for Duplicates**
###
Under the Data tab, we utilized the 'Remove Duplicates' feature to identify and eliminate duplicate entries from the dataset. This helped in streamlining the data and removing redundant information.
###
**Step 3: Cleaning the 'Party' Column**
###
The 'party' column exhibited various inconsistencies such as different spellings, hyphens, random dates, and blank entries. We applied filters to the column and manually corrected the entries to ensure uniformity and accuracy.
###
**Step 4: Standardizing Data Formats**
###
*	Utilized the Trim function to remove extra spaces in the 'vice' column, ensuring consistency.
*	Changed the data type of the 'salary' column from 'Currency' to 'Number' to facilitate seamless import into SQL. This step is crucial to avoid issues with special characters like '$' in SQL queries.
*	Standardized the date formats in the 'date updated' and 'date created' columns by selecting the 'Short Date' cell format, resolving inconsistencies in date representation.
###
**Step 5: Removing Redundant Data**
###
Identified and removed redundant columns such as 'prior' and the first column with numerical indices, which did not provide meaningful information for analysis. This step helped streamline the dataset and improve clarity.
###
**Conclusion**
###
By systematically applying various Excel functionalities and manual corrections, we successfully cleaned the 'Raw file US Presidents' dataset. The cleaned dataset is now ready for further analysis or integration into other platforms, ensuring data integrity and accuracy.



