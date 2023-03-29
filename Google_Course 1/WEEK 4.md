### MASTERING SPREADSHEET BASICS

FORMAT --> text wrapping

**Labelling** 
	-**ATTRITBUTE** - A characteristic or quality of data used to label a column in a table.

- In a dataset, a row is also called an **OBSERVATION**
			-  An **Observation** is all of the attributes for something contained in row of a data table.

**ORGANIZING DATA** - select columns with data -- > sort (under data menu).

**FORMULAS** - A set of instructions that performs a specific actiono using the data in a spreadsheet. 
		- Uses cell references. 



### SQL (Structured Query Language)

**Syntax** is the predetermined structure of a language that includes all required words, symbols, and punctuation, as well as their proper placement.

The syntax of every SQL query is the same: 

-   Use **SELECT** to choose the columns you want to return.  
-   Use **FROM** to choose the tables where the columns you want are located.
-   Use **WHERE** to filter for certain information.

--- (Base from sql.jpg)

The above query uses three commands to locate customers with the first name Tony:

1.  **SELECT** the column named **first_name**
    
2.  **FROM** a table named **customer_name** (in a dataset named **customer_data**) (The dataset name is always followed by a dot, and then the table name.)
    
3.  But only return the data **WHERE** the first_name is **Tony**

--- (Base from sql2.jpg)

The above query uses three commands to locate customers with the first name Tony.

1.  **SELECT** the columns named **customer_id**, **first_name**, and **last_name**
    
2.  **FROM** a table named **customer_name** (in a dataset named **customer_data**) (The dataset name is always followed by a dot, and then the table name.)
    
3.  But only return the data **WHERE** the first_name is **Tony**


###### Endless SQL possibilities

**Capitalization, indentation, and semicolons

- You can write sql queries in all lowercase and not worry about extra spaces.
- however, using capitalization and indentation can help you read the information more easily.
- **semicolons** The semicolon is a statement terminator and is part of the American National Standards Institute (ANSI) SQL-92 standard. 
	- is a recommended syntax for adoption by all SQL databases. (not all have  adopted this).

###### WHERE CONDITIONS 
		 -- **SELECT** clause identifies the column you want to pull data from by name.
		 -- **FROM** clause identifies the table where the column is located by name.
		 
the **WHERE** clause narrows your query so that the database returns only the data with an exact value match or the data that matches a certain condition that you want to satisfy.

For example, if you are looking for a specific customer with the last name Chavez, the WHERE clause would be: 

**WHERE field1 = 'Chavez'**

However, if you are looking for all customers with a last name that begins with the letters “Ch," the WHERE clause would be:

**WHERE field1 LIKE 'Ch%'**

You can conclude that the **LIKE clause** is very powerful because it allows you to tell the database to look for a certain pattern! 

**The percent sign (%)** is used as a wildcard to match one or more characters. In the example above, both **Chavez** and **Chen** would be returned.

Note that in some databases an asterisk (*) is used as the wildcard instead of a percent sign (%).

###### SELECTING ALL COLUMNS 

Can you use  **SELECT **  ?

(SELECT *) you would be selecting all of the columns in the table instead of the field1 column only. From a syntax point of view, it is a correct SQL statement, but you should use the asterisk (*) sparingly and with caution. Depending on how many columns a table has, you could be selecting a tremendous amount of data. Selecting too much data can cause a query to run slowly.


###### COMMENTS 

- Comments are text placed between certain characters (/* */)  or after two dashes (--).
- best use (--). 

###### ALIASES 

You can also make it easier on yourself by assigning a new name or **alias** to the column or table names to make them easier to work with (and avoid the need for comments).

This is done with a SQL **AS clause.**

An alias doesn’t change the actual name of a column or table in the database.


--------------- 

**<>** - means "does not equal"
The **AND** clause enables you to test for both conditions.


### DATA VISUALIZATION 

##### Planning a data visualization

###### Steps to plan a data visualization

- Explore the data for patterns
- Plan your visuals 
		- Next it is time to refine the data and present the results of your analysis
- Create your visuals
	- It involves trying different visualization formats and making adjustments until you get what you are looking for. In this case, a mix of different visuals will best communicate your findings and turn your analysis into the most compelling story for stakeholders.

######  Visualization software (Tableau)

Tableau is a popular data visualization tool that lets you pull data from nearly any system and turn it into compelling visuals or actionable insights.

###### Programming language (R with RStudio) 

A lot of data analysts work with a programming language called R. Most people who work with R end up also using RStudio, an integrated developer environment (IDE), for their data visualization needs. As with Tableau, you can create dashboard-style data visualizations using RStudio.


A pie chart shows how a whole is broken down into parts and is an effective visualization for a class broken down by age. 
A column chart shows categories and is an effective visualization for the ages of males versus females.