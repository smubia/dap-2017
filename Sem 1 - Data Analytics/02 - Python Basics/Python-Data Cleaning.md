# Data Cleaning
*Written by: Michael, Core Team 17*

## CONGRATULATIONS. 
### You are now embarking on the first lesson of DAP.
Hi everybody! I hope your midterms went well. It's time to get back to Data Analytics! I hope you still remembered everything that was gone through during the last 3 CLS. Don't worry, do this checklist before you continue on. You would be needing everything in the checklist for this lesson. For this lesson, we would only be going through Data Cleaning! Here is an overview of what we would be doing: 

**Things to include in the checklist**
- very related to pandas
- datetime
- Any data cleaning concepts

- [ ] Data Cleaning using Microsoft Excel
- [ ] Data Cleaning using Python Pandas


# Data Cleaning
What is data cleaning, and why is why is it important? Let's do this simple task. Let's say you have a excel file of records of all people in an organisation. How many different option do you think the column "gender" has. Only 2? You're wrong, [click here to find out.](https://docs.google.com/a/smu.edu.sg/spreadsheets/d/1z3YoRri8JAz1q3JPFp6x1S2vs3AcTZ_Yc--wSLUwO1A/edit?usp=sharing) This doesn't even include those [other gender options.](http://www.telegraph.co.uk/technology/facebook/10930654/Facebooks-71-gender-options-come-to-UK-users.html)

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
For today's lesson, we would be using both Microsoft Excel and Python for Data Cleaning. Why would you


Slow. (I wanted to put in something for you to try data cleaning a super big excel file, but I decided against it cause I don't want you guys to cry during CLS.)

I don't think its a choice of "Python & Panda" or "Excel." Rather, I view them as complimentary. I wouldnt use Panda to browse data (but you could), and I wouldn't use Excel as a tool to clean up data or automate tasks (but you could). I'd use the right tool at the right time for the job. 

Panda has a lot of power, but at a high level, the module is really good at two things:
1) Munging Data Sets: helping you clean up and put data together into a format that is easy to use, excel friendly, and analyze. 
2) Automating the clean up of data sets (missing data, incongruent dates in series,etc).

Excel is simply not good at these things. Even if you are a keyboard jockey, it can take hours and hours to clean up and get even the smallest data sets to the point where you can do things like pivot tables etc (think lots of selecting, cutting and pasting). 

To give a real world example, I use ad networks to monetize remnant inventory on my mobile apps. I use probably 10-15 ad networks (different apps, countries etc) and each ad network generates a csv file in a slightly different format. If I were to download each of these reports by hand each day and combine them into Excel, I would never have any time to actually analyze the results (not to mention the fact that this approach is fraught with the potential to create errors).  As result, I use Python and Pandas to take all my files, clean and combine them, and dump them into an Excel workbook.  THEN, I use Excel to browse, think about, and make decisions about the data. 

On the other hand, lets say I want to do a quick ad hoc analysis and I have a fairly neat, clean and reasonably sized (100s or 1000s of lines) data set (e.g. stock data), I'm probably not going to write a python script to analyze it in the early stages. Rather, Im just going to pull it into Excel, maybe put it into a pivot table and take a look at it and noodle on it some. If I decide that this is a data set I want to do something special with or I am going to be using this data over and over in the future, then I'll invest the time to write a script.

### When to use Data Cleaning for Excel of Python

## Data Cleaning using Microsoft Excel

## Data Cleaning using Python Pandas

## Additional Readings (Very Indepth)


---

# Mini Projects
## Project 1 (Uber Data)
https://riders.uber.com/trips
http://ummjackson.github.io/uber-data-extractor/
https://code.jquery.com/jquery-2.1.3.min.js
https://medialab.github.io/artoo/public/dist/artoo-latest.min.js

- The sample data that you can use.


---


# External Resources
