# Week 9 SGTA (External offering)

## Activity 1 - Date formats (10 minutes + 10 minutes discussion)

Both Excel and MATLAB offer the option to convert datetime values to text, and read dates from text, using different formats. Review the following information about the different format patterns available in each language:

* Excel date formats
  * Documentation from Microsoft: https://support.microsoft.com/en-us/office/format-a-date-the-way-you-want-8e10019e-d5d8-47a1-ba95-db95123d273e
* MATLAB date formats
  * Documentation from MATLAB: https://www.mathworks.com/help/matlab/ref/datetime.html#buhzxmk-1-Format

Fill the following table. The first row has been filled for your convenience.

| Date | Format in Excel | Format in MATLAB |
|---|---|---|
| 9/04/2014 | d/mm/yyyy | d/MM/yyyy|
| 09/04/2014 | 
| April 9, 14 | 
| Apr 29, 2014 9:41 PM | 
| 08-Mar-2015 19:25 | 


## Activity 2 - From Excel Dates to Text (15 minutes + 10 minutes discussion)

The following CSV file contains weather data from the US (FYI, the original file is from https://figshare.com/articles/weather_data_csv/5012747).

* [weather_data.csv](weather_data.csv)

Complete the following tasks.

1. Import the CSV file into an Excel spreadsheet. *Note that this is a large file and it may take time to import the file*. Remember the steps:

   1. Upload the CSV file to OneDrive.
   2. Click on the file to open it in Excel Online.
   3. Convert the file to Excel format.
2. Create the columns `Day`, `Month`, `Year` and use EXCEL formulas (`DAY`, `MONTH`, `YEAR`) to populate the columns.
4. Create the column `US format` and use the EXCEL formula (`TEXT`) to generate dates in US format using the `Day`, `Month`, and `Year` columns. In the US format, the month is written before the day. For example, if the date is `23/11/2014`, in US format it will be `11/23/2014`.

You can find documentation about the TEXT function here:
* https://support.office.com/en-us/article/combine-text-with-a-date-or-time-cef6a66c-8176-470c-ba85-4b030405dfbf
* https://support.office.com/en-us/article/text-function-20d5ac4d-7b94-49fd-bb38-93d29371225c


## Participation task

Download and submit the excel file (.xlsx) with your solution to activity 2 to the week 9 SGTA participation task submission box.

Your participation will count as satisfactory if you can correctly fill some of the `Day`, `Month`, and `Year` columns, and you have made a reasonable attempt to correctly fill the `US format` column.
