
### WORKING WITH SPREADSHEETS 

**SPREASHEET TASKS** 
- Organize your data
		- Pivot table
				- Sort and filter
- Calculate your data 

### FORMULAS IN SPREADSHEETS 

###### **Auto-filling**

The lower-right corner of each cell has a fill handle. It is a small green square in Microsoft Excel and a small blue square in Google Sheets.

-   Click the fill handle for a cell and drag it down a column to auto-fill other cells in the column with the same value or formula in that cell. 
    
-   Click the fill handle for a cell and drag it across a row to auto-fill other cells in the row with the same value or formula in that cell. 
    
-   If you want to create a numbered sequence in a column or row, do the following: 1) Fill in the first two numbers of the sequence in two adjacent cells, 2) Select to highlight the cells, and 3) Drag the fill handle to the last cell to complete the sequence of numbers. For example, to insert 1 through 100 in each row of column A, enter **1** in cell A1 and **2** in cell A2. Then, select to highlight both cells, click the fill handle in cell A2, and drag it down to cell A100. This auto-fills the numbers sequentially so you don't have to type them in each cell.

###### **Absolute referencing**

-   Absolute referencing is marked by a dollar sign ($). For example, =$A$10 has absolute referencing for both the column and the row value
    
-   Relative references (which is what you normally do e.g. “=A10”) will change anytime the formula is copied and pasted. They are in relation to where the referenced cell is located. For example if you copied “=A10” to the cell to the right it would become “=B10”. With absolute referencing “=$A$10” copied to the cell to the right would remain “=$A$10”. But if you copied $A10 to the cell below, it would change to $A11 because the row value isn't an absolute reference.
    
-   Absolute references will not change when you copy and paste the formula in a different cell. The cell being referenced is always the same.
    
-   To easily switch between absolute and relative referencing in the formula bar, highlight the reference you want to change and press the F4 key; for example, if you want to change the absolute reference, $A$10, in your formula to a relative reference, A10, highlight $A$10 in the formula bar and then press the F4 key to make the change.


###### **Data range**

-   When you click into your formula, the colored ranges let you see which cells are being used in your spreadsheet. There are different colors for each unique range in your formula.
    

-   In a lot of spreadsheet applications, you can press the F2 (or Enter) key to highlight the range of data in the spreadsheet that is referenced in a formula. Click the cell with the formula, and then press the F2 (or Enter) key to highlight the data in your spreadsheet.

###### **Combining with functions**

-   COUNTIF() is a formula and a function. This means the function runs based on criteria set by the formula. In this case, COUNT is the formula; it will be executed IF the conditions you create are true. For example, you could use **=COUNTIF(A1:A16, “7”)** to count only the cells that contained the number 7. Combining formulas and functions allows you to do more work with a single command.

###### Pro tip: Spotting errors in spreadsheets with conditional formatting

Conditional formatting can be used to highlight cells a different color based on their contents. This feature can be extremely helpful when you want to locate all errors in a large spreadsheet. For example, using conditional formatting, you can highlight in yellow all cells that contain an error, and then work to fix them.

###### **Conditional formatting in Microsoft Excel**

To set up conditional formatting in Microsoft Excel to highlight all cells in a spreadsheet that contain errors, do the following:

1.  Click the gray triangle above row number 1 and to the left of Column A to select all cells in the spreadsheet.
    
2.  From the main menu, click **Home**, and then click **Conditional Formatting** to select **Highlight Cell Rules > More Rules**.
    
3.  For Select a Rule Type, choose **Use a formula to determine which cells to format**.
    
4.  For Format values where this formula is true, enter **=ISERROR(A1)**.
    
5.  Click the **Format** button, select the Fill tab, select yellow (or any other color), and then click **OK**.
    
6.  Click **OK** to close the format rule window.
    

To remove conditional formatting, click Home and select Conditional Formatting, and then click Manage Rules. Locate the format rule in the list, click Delete Rule, and then click OK.

###### **Conditional formatting in Google Sheets**

To set up conditional formatting in Google Sheets to highlight all cells in a spreadsheet that contain errors, do the following:

1.  Click the empty rectangle above row number 1 and to the left of Column A to select all cells in the spreadsheet. In the [Step-by-step in spreadsheets](https://www.coursera.org/learn/ask-questions-make-decisions/lecture/lpuHf/step-by-step-in-spreadsheets "Step-by-step in spreadsheets") video, this was called the Select All button.
    
2.  From the main menu, click **Format** and select **Conditional Formatting** to open the Conditional format rules pane on the right.
    
3.  While in the Single Color tab, under Format rules, use the drop-down to select **Custom formula is,** enter **=ISERROR(A1)**, select yellow (or any other color) for the formatting style, and then click **Done**.
    

To remove conditional formatting, click Format and select Conditional Formatting, and then click the Trash icon for the format rule.


### FUNCTIONS IN SPREADSHEETS

you want to convert the number values in the Date column into text. You can use the **TEXT function** to do this

*The **TEXT** **function** converts a number into text according to a specified format.**

**=TEXT(B2,"mmmm").** The first entry (**B2**) refers to the cell you want to convert. The second entry (**“mmmm”**) refers to the specific format you want to use. Press **Enter**.

The **COUNTIF function** quickly counts how many items in a range of cells meet a given criterion

**=COUNTIF('raw data'!G:G,A2)**. The first entry ('raw data'!G:G) refers to the range where you are counting the data. The range is located on your **raw data** sheet (**'raw data'!**) and includes all column G (**G:G**). This column contains the data for months. The second entry (**A2**) refers to the criterion you want to count. In this case, it’s “January,” the value in cell A2 of your **summary data** sheet. The function will tell you how many times **January** (the criterion) appears in the **Date** column (the range).


### SAVE TIME WITH STRUCTURED THINKING 

To successfully solve a problem as a data analyst, you need to train your brain to think structurally. 

**A statement of work** is a document that clearly identifies the products and services a vendor or contractor will provide to an organization. It includes objectives, guidelines, deliverables, schedule, and costs.

**A scope of work** is project-based and sets the expectations and boundaries of a project. A scope of work may be included in a statement of work to help define project outcomes.

data has little value if it is not paired with context.

