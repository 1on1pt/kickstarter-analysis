# An Analysis of Kickstarter Funding Campaigns Based on Outcomes
Performing an analysis on Kickstarter data to uncover outcomes based on launch date *and* goals in funding campaigns.

## Overview of Project

A comprehensive analysis of Kickstarter campaigns was completed that included the timeframe of 2010 through 2017.  Overall data included such categories as film and video, food, games, journalism, music, photography, publishing, technology, and theater.  Subcatagory detail was also available and thus allowed for a more thorough analysis.  The ulitmate goal is to successfully fund the theater play, *"Fever"*.



### Purpose

The purpose of this project is to present an analysis of Kickstarter funding campaigns based on **launch date** and **funding goal outcomes** for plays that are performed in the theater.

## Analysis and Challenges



### Analysis of Outcomes Based on Launch Date

The **Analysis of Outcomes Based on Launch Date** was created first by adding a new column in the workbook, "Years", and then extracting the year from the "Date Created Conversion" column.  A new worksheet, *"Theater Outcomes by Launch Date"* was added along with a pivot table from the *"Kickstarter"* worksheet.  The pivot table was filtered for "Parent Category - theater" and "Years - ALL" with the column labels filtered to show "successful", "failed", and "canceled".  Below is the resulting line chart that visualizes the relationship between theater funding outcomes based on launch date.

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/94148420/147168457-8d8e82f3-9e5d-45e3-8346-b086b99fd550.png)


### Analysis of Outcomes Based Goals

The **Analysis of Outcomes Based Goals** was first created by adding a new worksheet, *"Outcomes Based on Goals"* to the Kickstarter_Challenge workbook.  On the new worksheet, the following columns were created to hold the data:

* Goal
* Number Successful
        * Number Failed
        * Number Canceled
        * Total Projects
        * Percentage Successful
        * Percentage Failed
        * Percentage Canceled
        

### Challenges and Difficulties Encountered



## Results
