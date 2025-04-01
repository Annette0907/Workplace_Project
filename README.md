# Workplace_Project

How to setup Github and fork repo
Create a folder where your documents will be stored on your PC.

Fork the repository in Github.com in the following manner:
- Go to the parent repository.
- In the top right corner of the page, click on the fork button.
- Select your github profile, which will create a fork.

Clone the forked repository in Github Desktop
- Open github desktop.
- Go to File > Clone Repository.
- In the Github.com tab, find the repository you have just forked.
- Select the repository and choose a local path for cloning, then click on clone.
- Click on "For own purpose".

Github Desktop should automatically track changes, but you can also initiate it in GitBash
- Open GitBash.
- Type the following:
-- cd C:/Path/to/file (where the files are stored) and press enter.
-- git init (to initialise tracking) and press enter.

Clone the Github repository in VS Code to work on the .ipynb file for coding
- Open VS Code.
- Go to View > Command Pallette (ctrl+shift+P).
- Type Git:Clone and select your repository.
- Choose a folder on your computer where you want to save your project.
- Once cloned, open the folder in VS code

## Data Cleaning Process
1.	Download the Excel file and clean data in excel.
2.	Create a copy of the worksheet in the same workbook – rename the new worksheet to cleaning insurance_claims.
3.	Select the entire dataset, and move it down a couple of rows to create some space to work in.
4.	In Column AO insert heading Count Blank – which will be used to count the number of blanks.
5.	Delete column AN as it is blank and will serve no purpose in the dataset.
6.	In 1st row of Count Blank column type the following formula =countblank([select the range where you want to count the blanks]) and press enter, copy/autofill the formula to all rows in Count Blank colum.
7.	Select the dataset and insert filters to filter the data.
8.	Filter to see data with 1 or more missing fields – Only 21 rows are affected and contains some fields with missing data.
9.	Insert new sheet to analyse impact of rows with missing data.
10.	Best course of action for large amount of data would be to delete the entire row of data.
11.	On analysis sheet, make note of number of rows that were removed.
12.	Clear filter on Count Blank column to show all data.
13.	Insert column at the beginning of dataset to calculate the min, max, median, mode and mean for each column copy or fill the formula for each column.
14.	Insert a pivot table to show the number of states.
15.	Go line by line to see whether the min, max, median, mode and mean makes sense.
16.	Insert Pivot table of entire dataset to gain more insights to assist with imputation values.
17.	Complete imputations of missing values
