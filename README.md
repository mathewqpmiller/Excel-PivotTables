# Excel-PivotTables

A deep dive into Excel Pivot Tables specializing on Data Analytics.

## Section 1: Excel Pivot Tables 101

* 1) Set up a view to show Budget by Title (as rows), with filters for Country (set to Japan) and Language (set to English). How many Japanese movies in the database were produced in English?

* 2) Clear the Language filter, set the Country filter to Denmark, and pull in Gross Revenue as a second metric. How much gross revenue did "The Celebration" generate?

* 3) Use the "Clear All" command in the PivotTable Analyze options to remove all fields from the table, and create a new view showing Gross Revenue by Country (as rows) and Genre (as columns). How much revenue was generated by Comedy films in Finland?

* 4) Remove the Country field, move Genre to the row labels, and drag in Rating as secondary row labels. How much revenue was generated by PG-rated Family films? Double click on the cell to see the exact source data populating the value. Which title drove most of the revenue?

* 5) Add a fake row of data in the "IMDb Movie Database" tab, beneath the existing rows, and use the Change Data Source option to update the pivot. Create a title-level view and confirm that the new data is included, then delete the entire row in the raw data sheet and refresh the Pivot Table to remove it.

|Budget by Title|Budget/GR by Country, Genre and Title|
|:-:|:-:|
|![Budget by Title](https://github.com/mathewqpmiller/Excel-PivotTables/blob/main/Images/Section1HomeworkPics/TitleBudgetPivotTable.png?h=350&w=630)|![Budget/GR by Country, Genre and Title](https://github.com/mathewqpmiller/Excel-PivotTables/blob/main/Images/Section1HomeworkPics/BudgetGROnCountryGenreTitle.png?h=350&w=630)|
|Horror Films GR by Country|USA B&W Films GR by Genre and Rating|
|![Horror Films GR by Country](https://github.com/mathewqpmiller/Excel-PivotTables/blob/main/Images/Section1HomeworkPics/GROnCountryByGenre.png?h=350&w=630)|![USA B&W Films GR by Genre and Rating](https://github.com/mathewqpmiller/Excel-PivotTables/blob/main/Images/Section1HomeworkPics/GROnGenreRatingByCountryB&W.png?h=350&w=630)|

### Add a row and a column to the raw dataset

<p align="center">
    <img src="https://github.com/mathewqpmiller/Excel-PivotTables/blob/main/Images/Section1HomeworkPics/Section1.5HomeworkPic.png?w=1260">
</p>

## Section 2: Formatting Excel Pivot Tables

* 1) Show Budget and Gross Revenue by Title, and change the number format to currency, with a dollar sign and no decimal places. What was the budget for "A Passage to India"?

* 2) Remove Budget and Title, and show Gross Revenue by Genre (rows) and Rating (columns). Update the PivotTable options to show "$0" instead of blank values

* 3) Move Rating to the row labels (beneath Genre), change your table layout to Outline View, and Update your column headers from "Rating" to "Film Rating", and from "Sum of Gross Revenue" to "Gross Revenue" (hint: you may need a trailing space)

* 4) Remove Film Rating from the view, so that you're just viewing Gross Revenue by Genre. Turn Grand Totals off, select the Gross Revenue values, format as currency (if they aren't already) and add a Color Scale from Green (high) to Red (low). Which Genre produced the most Gross Revenue?

* 5) Add a second instance of Gross Revenue, and format the new column with Data Bars. Update the number format to make the text invisible, so that only the bars appear. Which Genre produced the second-highest Gross Revenue total in the sample?

|A Passage To India GR|Replace Blank Values w/ $0|
|:-:|:-:|
|![A Passage To India GR](https://github.com/mathewqpmiller/Excel-PivotTables/blob/main/Images/Section2HomeworkPics/2.1HomeworkPic.png?h=350&w=630)|![Replace Blank Values w/ $0](https://github.com/mathewqpmiller/Excel-PivotTables/blob/main/Images/Section2HomeworkPics/2.2HomeworkPic.png?h=350&w=630)|
|Horror Films GR by Country|USA B&W Films GR by Genre and Rating|
|![Horror Films GR by Country](https://github.com/mathewqpmiller/Excel-PivotTables/blob/main/Images/Section2HomeworkPics/2.3HomeworkPic.png?h=350&w=630)|![USA B&W Films GR by Genre and Rating](https://github.com/mathewqpmiller/Excel-PivotTables/blob/main/Images/Section2HomeworkPics/2.4HomeworkPic.png?h=350&w=630)|

### Visualizing Gross Revenue with Color Values and Data Bars

<p align="center">
    <img src="https://github.com/mathewqpmiller/Excel-PivotTables/blob/main/Images/Section2HomeworkPics/2.5HomeworkPic.png?w=1260">
</p>

## Section 3: Use Pivot Tables to Sort, Filter and Group Data

* 1) Create a view showing Gross Revenue by Title, with a filter for Year to only include films released in 2005, 2006, 2007 or 2008, then sort the titles descending by Gross Revenue. What's the top-grossing film released during that 4-year sample? (Note: if the Release Dates don't auto-group, you will need to use the "Group" tools in the Analyze tab or create a new column in your raw data to extract the year from the Release Date column)

* 2) Add a Label Filter to only include titles that end in "2". How many sequels were released during these years? Which earned the most Gross Revenue?

* 3) Clear your label filter, and add a Value Filter to only show titles that earned between $1,000,000 and $3,000,000 in Gross Revenue. How many titles fell into this range?

* 4) Adjust your PivotTable Options to allow multiple filters, then add a label filter to only show movies that start with the letter "M". How many titles are now listed?

* 5) Add a wildcard to your label filter to only show titles that start with the letter "M" and also contain the letter "s", separated by any number of characters. Which titles are returned?

|Budget by Title|Budget/GR by Country, Genre and Title|
|:-:|:-:|
|![Budget by Title](https://github.com/mathewqpmiller/Excel-PivotTables/blob/main/Images/Section1HomeworkPics/TitleBudgetPivotTable.png?h=350&w=630)|![Budget/GR by Country, Genre and Title](https://github.com/mathewqpmiller/Excel-PivotTables/blob/main/Images/Section1HomeworkPics/BudgetGROnCountryGenreTitle.png?h=350&w=630)|
|Horror Films GR by Country|USA B&W Films GR by Genre and Rating|
|![Horror Films GR by Country](https://github.com/mathewqpmiller/Excel-PivotTables/blob/main/Images/Section1HomeworkPics/GROnCountryByGenre.png?h=350&w=630)|![USA B&W Films GR by Genre and Rating](https://github.com/mathewqpmiller/Excel-PivotTables/blob/main/Images/Section1HomeworkPics/GROnGenreRatingByCountryB&W.png?h=350&w=630)|

### Add a row and a column to the raw dataset

<p align="center">
    <img src="https://github.com/mathewqpmiller/Excel-PivotTables/blob/main/Images/Section1HomeworkPics/Section1.5HomeworkPic.png?w=1260">
</p>

## Section 4

## Section 5

## Section 6