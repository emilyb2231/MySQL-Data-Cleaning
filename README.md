# MySQL-Data-Cleaning

## Overview
This project takes the world layoffs dataset and focuses on cleaning and standardizing. The project focuses on standardizing dates, cleaning null and blank rows, deleting duplicate statements, and cleaning up input errors in data.

## Project Structure

### Create row_num column
-- Populates duplicate values by adding a row_num column that gives each entity a unique value.

### Removes duplicates
- Insert these values into the table.
- Effectively deletes all duplicate values.

### Standardizing data
- Trims blank white space from the edges of the table.
- Checks for issues in different data areas, such as mismatched Industry names, and sets them to the same value throughout the table.
- Fixes incorrectly inputted data, ensuring each value's data is matched throughout the table.
- Correctly formatting the date in the table.
- Changes the date from text value to date value.

### Gets rid of null and blank values
- Effectively checks data for any null and blank values and deletes those values from the table.

### Delete row_num column 
- Deletes row_num column after all data is standardized
