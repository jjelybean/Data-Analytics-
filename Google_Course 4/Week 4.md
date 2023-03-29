
### MANUALLY CLEANING DATA 

#### VERIFICATION AND REPORTS 

**VERIFICATION** - A process to confirm that a data-cleaning effort was well-executed and the resulting data is accurate and reliable.

**CHANGELOG** - A file containing a chronologically oredered list od modifications made to a project.

________________________

- **SEE THE BIG PICTURE WHEN VERIFYING DATA CLEANING

	- consider the business problem
	- consider the goal
	- consider the data

**USING FIND AND REPLACE**

- It is a toll that looks for a specified search term in a spreadsheet and allows you to replace it with something else.

**COUNTA** - a function that counts the total number of values within a specified range.

*In sql....*
**CASE STATEMENT** - The CASE statement goes through one or more conditions and returns a value as soon as a condition is met.

	![[Pasted image 20230326133818.png]]

___________________
## Correct the most common problems

Make sure you identified the most common problems and corrected them, including:

-   **Sources of errors**: Did you use the right tools and functions to find the source of the errors in your dataset?
    
-   **Null data**: Did you search for NULLs using conditional formatting and filters?
    
-   **Misspelled words**: Did you locate all misspellings?
    
-   **Mistyped numbers**: Did you double-check that your numeric data has been entered correctly?
    
-   **Extra spaces and characters**: Did you remove any extra spaces or characters using the **TRIM** function?
    
-   **Duplicates**: Did you remove duplicates in spreadsheets using the **Remove Duplicates** function or **DISTINCT** in SQL?
    

-   **Mismatched data types**: Did you check that numeric, date, and string data are typecast correctly?
    
-   **Messy (inconsistent) strings**: Did you make sure that all of your strings are consistent and meaningful?
    
-   **Messy (inconsistent) date formats**: Did you format the dates consistently throughout your dataset?
    
-   **Misleading variable labels (columns)**: Did you name your columns meaningfully?
    
-   **Truncated data:** Did you check for truncated or missing data that needs correction?
    
-   **Business Logic**: Did you check that the data makes sense given your knowledge of the business?


![[Pasted image 20230326134126.png]]

______________________________

#### DOCUMENTING RESULTS AND THE CLEANING PROCESS

**DOCUMENTATION** - Proces of tracking changes.

	BENEFITS:
		1) recalling the errors that were cleaned 
		2) informing others of the changes
		3) Determine the quality of data


-- *Changelogs are super useful for helping us understand the reasons changes have been made. Changelogs have no set format and you can even make your entries in a blank document. But if you are using a shared changelog, it is best to agree with other data analysts on the format of all your log entries.*

*Typically, a changelog records this type of information:  

-   Data, file, formula, query, or any other component that changed
    
-   Description of what changed
    
-   Date of the change
    
-   Person who made the change
    
-   Person who approved the change 
    
-   Version number 
    
-   Reason for the change*


_________________________________

In this reading, you will learn about some advanced functions that can help you speed up the data cleaning process in spreadsheets. Below is a table summarizing three functions and what they do:

![[Pasted image 20230326135639.png]]

https://www.coursera.org/learn/process-data/supplement/PLnRS/advanced-functions-for-speedy-data-cleaning


