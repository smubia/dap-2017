# Data Cleaning
*Written by: Michael, Core Team 17*

## CONGRATULATIONS. 
### You are now embarking on the first lesson on Data Analytics!
Hi everybody! I hope your midterms went well. It's time to get back to Data Analytics! I hope you still remembered everything that was gone through during the last 3 CLS. Don't worry, I believe that the best way of learning is to do projects. Also, if you have any questions do try to google for it and if it doesn't work, ASK! For this lesson, we would only be going through Data Cleaning! Here is an overview of what we would be doing: 

- [ ] Data Cleaning using Microsoft Excel
- [ ] Data Cleaning using Python Pandas


# Data Cleaning
What is data cleaning, and why is why is it important? Let's do this simple task. Let's say you have a excel file of records of all people in an organisation. How many different option do you think the column "gender" has. Only 2? You're wrong, [click here to find out.](https://docs.google.com/a/smu.edu.sg/spreadsheets/d/1z3YoRri8JAz1q3JPFp6x1S2vs3AcTZ_Yc--wSLUwO1A/edit?usp=sharing) This doesn't even include [other gender options.](http://www.telegraph.co.uk/technology/facebook/10930654/Facebooks-71-gender-options-come-to-UK-users.html)

With the many different option for gender, imagine the different ways that other options can have! We need clean the data such that there is only 2 different columns so that we can visualise data/ conduct data analysis. 

**DID YOU KNOW?** You probably have done data cleaning before. You just didn't know that it was part of data cleaning. Here are some examples of data cleaning:

1. Looked at an excel sheet, found mistake and edited it.
2. Changed data format from MM-DD-YYYY to DD-MM-YYYY or anything similar
3. Remove columns or rows as the data was rubbish/doesn't make sense
4. Capitalise Names (changing from michael ONG --> Michael Ong)
5. Change the format of "Profit" from text to currency/number 
6. Pivot an excel table
7. Create a new column "Full name" from the "First name" and "Last Name"

These all are examples of data cleaning! Let's get started shall we!


## Excel vs. Python
For today's lesson, we would be using both Microsoft Excel and Python for Data Cleaning. But why are some of the reasons why SMUBIA require you to learn both Excel and Python. Why not just use Excel or why not just use Python? **Check out below for the reasons.**


| Excel| Python| Winner|
| ------------- |-------------| -----|
| Faster to Clean      | Slower to Clean | Excel |
| Simple click and edit      | Cannot click and edit      |   Excel |
| Simple learning curve  |  Steeper learning curve      |   Excel  |
| Simple functions for cleaning  |  Complex functions for cleaning      |   Python  |
| Can take limited amount of data    |  Can take any amount of data      |   Python  |
| Longer processing time  |  Shorter processing time      |   Python  |
| No automated processing of data  |  Automated processing of data      |   Python  |
| Take a long time to clean large datasets  |    Take a shorter time to clean large datasets    |   Python  |
| Less robust merging of data  |  More robust merging of data     |   Python  |

Do note that in this CLS, we are not trying to tell you to use Python over Excel as Python > Excel. But it is to tell you that both have a certain time and place to use them. **The rule of thumb is that if the data is for a one-off cleaning and/or usually for a quick insight generation and/or the data is not overally huge.*** Then by all means, please use Microsoft Excel and don't spend time writing scripts that you would most probably never use again. 

Use Python when you are dealing with dealing with a dataset with the following characteristics
1. Is too Big, and/or require a long time to process.
2. You are going to analyse it more than once due to the constant stream of data.
3. There are complex functions that you need to do, which microsoft excel do not have.

If your dataset has any of the following characteristics, then it's better to invest in building a script to clean the data.

## Data Cleaning using Microsoft Excel
For Data Cleaning using Microsoft Excel, I've included various videos on data cleaning including very basic functions. Feel free to skip topics that you already understand.

:tv: **Basic Data Cleaning** - https://www.youtube.com/watch?v=sB0nJlcjFBs (until 6:02) <br/>
:tv: **Cool Data Cleaning Tricks** - https://www.youtube.com/watch?v=e0TfIbZXPeA <br/>
:tv: **Data Cleaning in Excel Pt 1** - https://www.youtube.com/watch?v=Jt76Q0dVEm4 <br/>
:tv: **Data Cleaning in Excel Pt 2** - https://www.youtube.com/watch?v=WRk9t5yo5Zs <br/>
:tv: **Vlookup, Merging Datasets, Hlookup** - https://www.youtube.com/watch?v=CqIY_60GvOs <br/>

Once you are done with data cleaning, here is a project for you to do. I have web scrapped my [uber trips data](https://drive.google.com/open?id=0B4co3D7kCi9oVXE0dXpXVF9GZnM), and I would want to analyse it. Inside the file, there is 2 sheets the excel file. One with the raw data, and another with the cleaned data. Using the methods that you learn in this course or other methods that you learnt, clean the data until the raw data looked like the cleaned data sheet. I've highlighted those columns that I added into the file.

Below is the list of the things that I have cleaned:
- Remove all empty Values.
- Some columns have very weird values, remove them as well.
- Clean the date from 2 different date time formats into a single date time format. (It has to be "DD/MM/YYYY")
- Add a column for Year, Month, Time & Hour
- Capitalize Names of Driver (eg. Michael ONG --> Michael Ong)
- Categorize the column (if UberPOOL, the column would state that it's 1, else 0.)
- Clean the data such that the currency can be used for Calculations, check it by doing a SUM at the end. (The cleaned sheet has this)
- Calculate the time taken each trip

## Data Cleaning using Python Pandas
Do note that the first time cleaning with Python, you will know that it is extremely hard to clean and would want to go back to Excel. But, if you do wish to do data analytics in the future, you need to know that the amount of data that you would be handling is definitely better of using Python/Pands. Companies like Uber store 500TB of data a day. 

### PIERIAN DATA ###
**Data input and Output** (Skip SQL)<br>
Outcomes: Read csv, read excel, read HTML<br>
** You don't have to install anything.<br>
:tv: https://drive.google.com/open?id=0B4co3D7kCi9oX2l1MEl6a1B3bDA

**DataFrame Pt 1**<br>
Outcomes: Creating a dataframe, slicing columns, creating new column, dropping rows & Columns, selecting cell.<br>
:tv: https://drive.google.com/open?id=0B4co3D7kCi9oNjd5U3RBVGJvUE0

**DataFrame Pt 2**<br>
Outcomes: data filtering<br>
:tv: https://drive.google.com/open?id=0B4co3D7kCi9oYVlUUjZzbXFLTDA

**Missing Data**<br>
Outcomes: How to deal with missing values<br>
:tv: https://drive.google.com/open?id=0B4co3D7kCi9oeUsyeWhaSHJMQ0k

**Merging, Joining & Concatenation**<br>
Outcomes: Merging Dataframes, Joining Dataframes and Concatenating Dataframes<br>
:tv: https://drive.google.com/open?id=0B4co3D7kCi9oaFNvMmhKS3gzSTQ

**Pandas Operations**<br>
Outcomes: Counting occurances, no. of unique values, running a function on all dataframes, sorting values, Pivot tables<br>
:tv: https://drive.google.com/open?id=0B4co3D7kCi9oQm1vSzczVUcxT0E

**Date & Times** [UFO Data](https://drive.google.com/open?id=0B4co3D7kCi9oN2ltcFNmNzdMTVk)<br>
Outcomes: Cleaning Date, Cleaning Time, dealing with Date and Time.<br>
:tv: https://www.youtube.com/watch?v=yCgJGsg0Xa4

**Creating Dummy Variables**<br>
Outcome: Creating dummy variables [Titanic Dataset](https://drive.google.com/open?id=0B4co3D7kCi9oWHhXdTNvX1RESGM)<br>
:tv: https://www.youtube.com/watch?v=0s_1IsROgDc

Once you are done with all the videos, do the same thing that you did in [Excel](https://drive.google.com/open?id=0B4co3D7kCi9oT3N1R3BPa083UUE), and try to make it exactly like the desired output. Since it's the first time that you do data cleaning, you may find it extremely hard. Just try your best to do it! 

---

# That's all folks #
## We would be continuing with Data Analytics with Data Visualisation (Tableau) next week! ##
