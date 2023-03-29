
DIRTY DATA - Data that is incomplete, incorrect, or irrelevant to the porblem you're trying to solve.

CLEAN DATA

DATA ENGINEERS - Transform data into useful format for analysis and give it infrastructure. 

DATA WAREHOUSING SPECIALISTS - Develop processes and procedures to effectively store and organize data.

#### TYPES OF DIRTY DATA 

**DUPLICATE DATA** - Any data record that shows up more than once

**OUTDATED DATA**
**INCOMPLETE DATA**

**INCORRECT/INACCURATE DATA** - any data that is complete but inaccurate.

**INCONSISTENT DATA**
-Any data that uses different formats to represent the same thing 

-------------
FIELD LENGTH - A tool for determining how many characters can be keyed into a field.

DATA VALIDATION - A tool for checking the accuracy and quality of data vefore adding or importing it.

-----------------------------------------

#### DATA CLEANING TOOLS AND TECHNIQUES 

- Keep a copy of the original data


- removing unwanted data
- removing spaces and blanks 
- removing irrelevant data
- fixing misspellings, inconsistent capitalization, incorrect punctuation and other typos
- removing formatting 


MERGER an agreement that unites two organizations into a new single new one

DATA MERGING the process of combining two or more datasets into a single dataset

--------------------------

The first question I would ask is, 

do I have all the data I need? 

To gather customer purchase insights, 

I wanted to make sure I had data on customers, 

their purchases, and where they shopped. 

Next I would ask, 

does the data I need exist within these datasets? 

As you learned earlier in this program, 

this involves considering 

the entire dataset analytically. 

Looking through the data before I start using 

it lets me get a feel for what it's all about, 

what the schema looks like, 

if it's relevant to my customer purchase insights, 

and if it's clean data. 

That brings me to the next question. 

Do the datasets need to be 

cleaned, or are they ready for me to use? 

Because I'm working with more than one source, 

I will also ask myself, 

are the datasets cleaned to the same standard? 

For example, what fields are regularly repeated? 

How are missing values handled? 

How recently was the data updated? 

Finding the answers to 

these questions and understanding 

if I need to fix any problems 

at the start of a project is 

a very important step in data merging. 

In both of the examples we explored here, 

data analysts could use 

either the spreadsheet tools or SQL queries to clean up, 

merge, and prepare the datasets for analysis. 

Depending on the tool you decide to use, 

the cleanup process can be simple or very complex. 

Soon, you'll learn how to make 

the best choice for your situation. 

As a final note, programming languages like R 

are also very useful for cleaning data. 

You'll learn more about how to use 

R and other concepts we covered soon.

------------------

Common mistakes to avoid

- **not checking for spelling errors**
- **forgetting to document errors** >> Documenting errors can help you in the future by showing how you resolved them.
- **Not checking for misfielded values**. >> a misfielded value happens when the values are entered into the wrong field
- **overlooking missing values**
- **only  looking at a subset of data**
- **Losing track of business objectives**: When you are cleaning data, you might make new and interesting discoveries about your dataset-- but you don’t want those discoveries to distract you from the task at hand.
- **Not fixing the source of the error:** Fixing the error itself is important. But if that error is actually part of a bigger problem, you need to find the source of the issue.
- **Not analyzing the system prior to data cleaning:** If we want to clean our data and avoid future errors, we need to understand the root cause of your dirty data.
- **not backing up your data prior to cleaning**
- **not accounting for data cleaning in your deadline/process**

--------------


# Hands-On Activity: Cleaning data with spreadsheets

Practice Quiz. • 1h. • 2 total points available.2 total points

### 1.

Question 1

![](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/vNOHJCCaThCThyQgmt4Qkg_87d7b2e3317d4900839e6a05c1df2937_lightbulb-HandsOn.png?expiry=1673481600000&hmac=QjY2-xlFVRAf9KrCyJfKzXe5yE0Nn1P9nv4CMrBLkRo)

## Activity overview

![](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/3UWxlyqNRxaFsZcqjZcWgQ_3fd91ae61ce04caaa755c3477a337947_line-y.png?expiry=1673481600000&hmac=OtqOW8mUofbJigV4Hqpz9I7yxFCiH0NSrGhAXkf6HHQ)

You’ve learned about cleaning data and its importance in meeting good data science standards. In this activity, you’ll do some data cleaning with spreadsheets, then transpose the data.

By the time you complete this activity, you will be able to perform some basic cleaning methods in spreadsheets. This will enable you to clean and transpose data, which is important for making data more specific and accurate in your career as a data analyst.

![](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/CFXPehkSRuWVz3oZEjblHw_d13dd2c679b54e48a7b8aa583227e281_graphic-line-right.png?expiry=1673481600000&hmac=JJHTqs6OXErivVX8eFaUOqOuEWq_ipeIcBotD3bn04E)

### What you will need

To get started, first access the data spreadsheet.

To use the spreadsheet for this course item, click the link below and select “Use Template.” 

Link to data spreadsheet: [Cleaning with spreadsheets](https://docs.google.com/spreadsheets/d/1PkAbgXC7C1g2dKzCCpaHBcAyPw-s1z7iUxIEJ0cCYWQ/template/preview "Cleaning with spreadsheets")

OR

If you don’t have a Google account, you can download the template directly from the attachment below.

[

Data Spreadsheet for Cleaning with Spreadsheets

XLSX File







](https://d3c33hcgiwev3.cloudfront.net/9Ss-5kXlRP6rPuZF5VT-qA_d5c83c4e13d643cd87cb22632fcaa9c6_Data-Spreadsheet-for-Cleaning-with-Spreadsheets.xlsx?Expires=1673481600&Signature=OzzkHe3EYP9u91P1UzFA9xmzXZ1bEBhgb9bNDeoi7VsNaRwM4zRQ7JiWTvL6CCq9sJ-yLGZzjclupwXq9UroVG7xq42cioirIcvgoZqWIHFIJnqr8EpTltZyNkXzbizGKLbRbXsmhV5CW~IJfnfteae~0ujTuVixRUIScb28-XA_&Key-Pair-Id=APKAJLTNE6QMUY6HBC5A)

![](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/Egx9CtOvTn2MfQrTr659HQ_7ea3cfec2f8b4b6d9a925e1a9980170e_graphic-line-left.png?expiry=1673481600000&hmac=bsDosv2TKyBMMgqAUyOH7GwyMBDoyMw7t7FXKTNmGiA)

## Select and remove blank cells

![](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/3UWxlyqNRxaFsZcqjZcWgQ_3fd91ae61ce04caaa755c3477a337947_line-y.png?expiry=1673481600000&hmac=OtqOW8mUofbJigV4Hqpz9I7yxFCiH0NSrGhAXkf6HHQ)

The first technique we’ll use is to select and eliminate rows containing blank cells by using filters. To eliminate rows with blank cells:

1. Highlight all cells in the spreadsheet. You can highlight **Columns A-H** by clicking on the header of **Column A**, holding **Shift**, and clicking on the header of **Column H**.

2. Click on the **Data** tab and pick the **Create a filter** option. In Microsoft Excel, this is called **Filter**.

![](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/O9NNCnlDSnWTTQp5Q1p1XA_25d78d3867c8402da3bafff30662affe_DAC4M2L3HO1-ss1---Hands-on-Activity---Cleaning-with-Spreadsheets.png?expiry=1673481600000&hmac=nE_7eNrrTVsjRmjQ3_4K7TzMhaU7Sc6XzTQzMf198GM)

Excel:

![](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/rbruHkUVR2e67h5FFVdnIA_46544fd0693e4d54b0b48738dd7adef1_clean1.png?expiry=1673481600000&hmac=chRJcHamfBeE69GdGceBf_xdGTlEjs7q9VdixEPkbSk)

3. Every column now shows a green triangle in the first row next to the column title. Click the green triangle in **Column B** to access a new menu.

4. On that new menu, click **Filter by condition** and open the dropdown menu to select **Is empty.** Click **OK**.

In Excel, click the dropdown, then **Filter...** then make sure only **(Blanks)** is checked. Click **OK**.

![](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/OnScbk09Sya0nG5NPSsmnw_3bd0ebe89bb54e78b77e287c57d84469_DAC4M2L3HO1-ss2---Hands-on-Activity---Cleaning-with-Spreadsheets.png?expiry=1673481600000&hmac=iLJq6bN4pkCp1BKlSaV7dISlvE56LZPQNo1-dD2mBjI)

Excel:

![](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/Uhm2BhPySXGZtgYT8nlxrw_665641702fca449eaa1d0d76780d93f1_clean2.png?expiry=1673481600000&hmac=u5xvDUtC2tw0GUvjAA4lqUS05ZeK9Uf-p85nNvWMH0Y)

![](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/fRE5xga-RnSROcYGvvZ0uw_899befc39c474834a28b47e8173acff1_image-1-.png?expiry=1673481600000&hmac=KtLx2mww0NiHBPSTGPbcONQjw8jMx9nM4F0YxOXnP_g)

You can then review a list of all the rows with blank cells in that column. 

5. Select all these cells and delete the rows except the row of column headers.

6. Return to the **Filter by condition** and return it to **None**. In Excel, click **Clear Filter from ‘Column’**. 

-   **Note:** You will now notice that any row that had an empty cell in **Column A** will be removed (including the extra empty rows after the data).
    

7. Repeat this for **Columns B-H**.

All the rows that had blank cells are now removed from the spreadsheet.

## Transpose the data

![](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/3UWxlyqNRxaFsZcqjZcWgQ_3fd91ae61ce04caaa755c3477a337947_line-y.png?expiry=1673481600000&hmac=OtqOW8mUofbJigV4Hqpz9I7yxFCiH0NSrGhAXkf6HHQ)

The second technique you will practice will help you convert the data from the current long format (more rows than columns) to the wide format (more columns than rows). This action is called **transposing**. To transpose your data:

1. Highlight and copy the data that you want to transpose including the column labels. You can do this by highlighting **Columns A-H**. In Excel, highlight only the relevant cells (**A1-H45**) instead of the headers.

2. Right-click on **cell I1**. This is where you want the transposed data to start.

3. Hover over **Paste Special** from the right-click menu. Select the **Transposed** option. In Excel, select the **Transpose** icon under the paste options.

![](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/MTwQTUO9Sr28EE1Dvcq9TA_72cc515a56e74c5087f79f9f0a5c76f1_Screenshot-2021-08-01-11.09.05-PM.png?expiry=1673481600000&hmac=5PmBf1qqfHKAXQvQkqrjeW_uM-OobdQ9anlnN0e3LP8)

Excel:

![](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/cZZMekh0R--WTHpIdIfvyQ_d00c1398f40f40c793f389815300b4f1_clean3.png?expiry=1673481600000&hmac=5vj5PN-bYBMicbB_QCimtr_R0y3KnFJe5pfCJFJS7tA)

You should now find the data transformed into the new wide format. At this point, you should remove the original long data from the spreadsheet.

4. Delete the previous long data. The easiest way to do this is to click on **Column A**, so the entire column is highlighted. Then, hold down the **Shift** key and click on **Column H**. You should find these columns highlighted. Right-click on the highlighted area and select **Delete Columns A - H**.

![](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/FFf0RtUlQHuX9EbVJdB7pQ_555c8bf1f03f493594dc266e0aeb64b7_cleaning1.png?expiry=1673481600000&hmac=qLm52kCC6m_oA1K9WPe3vbIBNDO9ANaTt2zIj91aEAw)

Your screen should now appear like this:

![](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/B-rP6lYRQiCqz-pWEWIg4g_0279fd307ac24ed5a9ad2687129d7757_cleaning2.png?expiry=1673481600000&hmac=pNLqrDkQNZesY4RUrtitUefKZvqaYjzXADi7Ye6cqsI)

## Get rid of extra spaces in cells with string data

![](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/3UWxlyqNRxaFsZcqjZcWgQ_3fd91ae61ce04caaa755c3477a337947_line-y.png?expiry=1673481600000&hmac=OtqOW8mUofbJigV4Hqpz9I7yxFCiH0NSrGhAXkf6HHQ)

Now that you have transposed the data, eliminate the extra spaces in the values of the cells.

1. Highlight the data in the spreadsheet.

2. Click on the **Data** tab, then hover over **Data cleanup** and select **Trim whitespace**.

![](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/pq0CjzcvSMOtAo83L7jD1A_cc5e405f6d2a41098cce951e3eacc8f1_Screenshot-2021-08-02-12.08.23-AM.png?expiry=1673481600000&hmac=FqKi6CyJF9nblw1nBL4LJ6wwb9zoZ6ertb7H7evFzP8)

In Excel, you can use the TRIM command to get rid of white spaces. In any space beneath your data (such as cell **A10**), type =TRIM(A1). Then, drag the bottom right corner of the cell to the bottom right to call the data without the white spaces.

Now all the extra spaces in the cells have been removed.

## Change Text Lower/Uppercase/Proper Case 

![](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/3UWxlyqNRxaFsZcqjZcWgQ_3fd91ae61ce04caaa755c3477a337947_line-y.png?expiry=1673481600000&hmac=OtqOW8mUofbJigV4Hqpz9I7yxFCiH0NSrGhAXkf6HHQ)

Next, you’ll process string data. The easiest way to clean up string data will depend on the spreadsheet program you are using. If you are using Excel, you’ll use a simple formula. If you are using Google Sheets, you can use an Add-On to do this with a few clicks. Follow the steps in the relevant section below.

### Microsoft Excel

![](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/m1U8W60bRHWVPFutG7R1Xg_6ccc659ce432491f86146109849dbf6b_shortline-y.png?expiry=1673481600000&hmac=lFwHITfKVcKeJd8GUdNc3AxKG3Kl7WVtSH56npWrJUU)

If you are using Microsoft Excel, [this documentation](https://support.microsoft.com/en-us/office/change-the-case-of-text-in-excel-adc65f5b-958f-46a2-4d23-ab4d5faf48a8) explains how to use a formula to change the case of a text string. Follow these instructions to clean the string text and then move on to the confirmation and reflection section of this activity. 

### Google sheets

![](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/m1U8W60bRHWVPFutG7R1Xg_6ccc659ce432491f86146109849dbf6b_shortline-y.png?expiry=1673481600000&hmac=lFwHITfKVcKeJd8GUdNc3AxKG3Kl7WVtSH56npWrJUU)

If you’re completing this exercise using Google Sheets, you’ll need to install an add-in that will give you the functionality needed to easily clean string data and change cases. 

_Google Sheets Add-on Instructions:_

1.  Click on the **Add-Ons** option at the top of Google Sheets.
    
2.  Click on **Get add-ons**.
    
3.  Search for **ChangeCase**. It should appear like this:
    

![screenshot of Add-on menu. Changecase installation is highlighted](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/RsIWudCiRKiCFrnQomSo4Q_a833e87b50d94bacaab8d47e49adef7b_DAC4M2L3SR1---image7.png?expiry=1673481600000&hmac=EfJQxo5h9jS9eoaOh6qfyqd8HkxVGaMYJXqc4m28CGA)

4. Click on **Install** to install the add-on. It may ask you to login or verify the installation permissions. 

Once you have installed the add-on successfully, you can access it by clicking on the **Add-ons** menu again. 

Now, you can change the case of text data that shows up. To change the text in Column C to all uppercase:

1. Click on **Column C**. Be sure to deselect the column header, unless you want to change the case of that as well (which you don't).

2. Click on the **Add-Ons** tab and select **ChangeCase**. Select the option **All uppercase**. Notice the other options that you could have chosen if needed.

![](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/s0nWbQUzQ8WJ1m0FM8PF-w_08d52b8bd2864249b631b86dd41db56a_cleaning4.png?expiry=1673481600000&hmac=7LpRyjHhMFs-zpyqJJA03wQ1LriF8LypzKPKp38z_YI)

## Delete all formatting

![](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/3UWxlyqNRxaFsZcqjZcWgQ_3fd91ae61ce04caaa755c3477a337947_line-y.png?expiry=1673481600000&hmac=OtqOW8mUofbJigV4Hqpz9I7yxFCiH0NSrGhAXkf6HHQ)

If you want to clear the formatting for any or all cells, you can find the command in the **Format** tab. To clear formatting:

1. Select the data for which you want to delete the formatting. In this case, highlight all the data in the spreadsheet by clicking and dragging over **Rows 1-8.**

2. Click the **Format** tab and select the **Clear Formatting** option.

In Excel, go to the **Home** tab, then hover over **Clear** and select **Clear Formats**.

You will notice that all the cells have had their formatting removed.

## Confirmation and reflection

![](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/3UWxlyqNRxaFsZcqjZcWgQ_3fd91ae61ce04caaa755c3477a337947_line-y.png?expiry=1673481600000&hmac=OtqOW8mUofbJigV4Hqpz9I7yxFCiH0NSrGhAXkf6HHQ)

Review the final product of the spreadsheet you cleaned during this activity. Which of the following is the rightmost column?

1 point

Column Z

Column AZ

Column AS

Column AA

### 2.

Question 2

In this activity, you practiced cleaning and transposing data. In the text box below, write 2-3 sentences (40-60 words) in response to each of the following questions:

-   What was the most challenging part of cleaning the data?
    
-   Why is cleaning and transposing data important for data analysis?
    
-   If you had to clean this data again, what would you do differently? Why?
    

1 point

Your answer cannot be more than 10000 characters.

Coursera Honor Code  [Learn more](https://learner.coursera.help/hc/articles/209818863)

I, **Angel Jasmine Borja**, understand that submitting work that isn’t my own may result in permanent failure of this course or deactivation of my Coursera account.

SubmitSave draft

Like

Dislike

Report an issue