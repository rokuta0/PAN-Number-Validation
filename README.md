# PAN-Number-Validation

This project focuses on cleaning and validating Indian PAN numbers from a given dataset.
The goal is to check whether each PAN number follows the official PAN format and classify it as Valid or Invalid.

**What I Did**

*Cleaned the raw PAN dataset by*:


1.  Handling missing PAN values


2.  Removing duplicate records


3.  Trimming extra spaces


4.  Converting PAN numbers to uppercase



*Validated PAN numbers based on official rules:*

1.  Exactly 10 characters long


2.  First 5 characters are letters


3.  Next 4 characters are digits


4.  Last character is a letter


5.  No repeated adjacent characters


6.  No complete alphabetical or numerical sequences



*Categorized PAN numbers into:*

1.Valid PAN


2.Invalid PAN


*Generated a summary report showing:*


1.  Total records processed


2.  Total valid PANs


3.  Total invalid PANs


4.  Total missing or incomplete PANs


**Tools & Technologies Used**

SQL (for data cleaning and validation logic)

Excel dataset (input data)
