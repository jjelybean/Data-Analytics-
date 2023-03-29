![[Pasted image 20230324093038.png]]

< link to this optional activity> https://www.coursera.org/learn/process-data/supplement/kt8qL/optional-upload-the-customer-dataset-to-bigquery 
![[Pasted image 20230324100132.png]]  


### **SELECT** 
	to specify what data
### **FROM** 
	pull data from any table

*sample* 
	![[Pasted image 20230324101709.png]]

#### ***Create table and Drop table if exists***

**To select unique pieces of data from the table (use distinct)**

	SYNTAX: DISTINCT col

![[Pasted image 20230324103232.png]]

**Functions to handle string variables**

length 

	SYNTAX: LENGTH()

![[Pasted image 20230324103545.png]]

to change or view a piece of data which is different from others![[Pasted image 20230324103621.png]]     

**substr()**  - (example is when abbreviating state names)
![[Pasted image 20230324103810.png]]
![[Pasted image 20230324103817.png]]


**trim()   - can remove any spaces, 
trim(col you want to trim spaces or extra letters from) = 'oh'** 

< link > of a hands on act

https://www.coursera.org/learn/process-data/quiz/kU8TQ/hands-on-activity-clean-data-using-sql/attempt

![[Pasted image 20230324105304.png]]

![[Pasted image 20230324105505.png]]
![[Pasted image 20230324105633.png]]

![[Pasted image 20230324105912.png]]


< another optional activity >

https://www.coursera.org/learn/process-data/supplement/kFRhX/optional-upload-the-store-transactions-dataset-to-bigquery

---------------------------------

CAST() - can convert anything from one data type to another

	SYNTAX: CAST(fielf you  to change AS data_type)
	
![[Pasted image 20230326125536.png]]


>> to sort the order use 
>> 	**ORDER BY 
>> 		*name of col*   DESC(descending)

**TYPECASTING** 
	- Converting data from one type to another.


_________________
![[Pasted image 20230326125805.png]]


**CONCAT()** - Adds strings together to create new text strings that can be used as unique keys

		SYNTAX: CONCAT(col1, col2) AS newCol

**COALESCE()** - Can be used to return non-null values in a list.

		SYNTAX: COALESCE(*column to check first*, column to check second when the first isnt available) AS newCol



![[Pasted image 20230326130643.png]]



----------------------------------

## SUMMARY

So far, you have been introduced to many different tools available in SQL. As a brief review, you learned how to complete tasks such as:

-   Getting data from a table using **SELECT** statements.
    
-   De-duplicating data using commands like **DISTINCT** and **COUNT +** **WHERE**.
    
-   Manipulating string data with **TRIM()** and **SUBSTR**.
    
-   Creating/dropping tables with **CREATE TABLE** and **DROP TABLE**.
    
-   Changing data types with **CAST**.
    

Some of these tasks are more challenging than others, and learning all the various SQL functions takes work. But, when you practice different functions, you can master the skills needed to make SQL work the way you need it to. Take a moment to think about the parts of SQL that you’ve found most challenging.


