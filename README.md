DAX Functions Overview 📊
This repository provides an overview and examples of different DAX (Data Analysis Expressions) functions used in Power BI, Excel, and other Microsoft tools. DAX is a powerful language used for data manipulation and analytics, specifically in business intelligence platforms.

Contents:
Date & Time Functions ⏰
Logical Functions ✅
Text Functions ✍️
1. Date & Time Functions ⏰
DAX provides several functions to manipulate date and time data. These functions allow you to perform operations like extracting parts of a date (day, month, year), calculating time differences, and formatting dates.

Common Date & Time Functions:
TODAY(): Returns the current date 📅
NOW(): Returns the current date and time 🕒
YEAR(<date>): Extracts the year from a given date 📆
MONTH(<date>): Extracts the month from a given date 📅
DAY(<date>): Extracts the day from a given date 📅
DATE(year, month, day): Returns a date given the year, month, and day as arguments 🗓️
DATEDIFF(<start_date>, <end_date>, <unit>): Returns the difference between two dates in the specified unit (e.g., year, month, day) 📅
DATEADD(<date>, <number_of_intervals>, <interval>): Adds a specified number of intervals to a date ⏳

2. Logical Functions ✅
Logical functions in DAX allow you to perform logical comparisons, return true/false values, and control the flow of calculations based on specific conditions.

Common Logical Functions:
IF(<condition>, <true_value>, <false_value>): Returns a value depending on whether the condition is true or false 🔄
AND(<condition1>, <condition2>): Returns TRUE if both conditions are true ✅
OR(<condition1>, <condition2>): Returns TRUE if either condition is true 🔄
NOT(<condition>): Reverses the result of a condition (TRUE becomes FALSE, and vice versa) 🔄
SWITCH(<expression>, <value1>, <result1>, <value2>, <result2>, ...): Evaluates an expression against multiple values and returns the corresponding result 🔄

3. Text Functions ✍️
Text functions in DAX are used to manipulate string values. You can extract substrings, concatenate text, and format text values.

Common Text Functions:
CONCATENATE(<text1>, <text2>): Combines two text strings into one ✨
LEFT(<text>, <num_chars>): Extracts the leftmost characters from a text string ⬅️
RIGHT(<text>, <num_chars>): Extracts the rightmost characters from a text string ➡️
LEN(<text>): Returns the length of a text string 📏
TRIM(<text>): Removes leading and trailing spaces from a text string ✂️
UPPER(<text>): Converts a text string to uppercase 🔠
LOWER(<text>): Converts a text string to lowercase 🔡
REPLACE(<old_text>, <start_num>, <num_chars>, <new_text>): Replaces part of a text string with new text 🔄
SEARCH(<substring>, <text>, <start_num>): Searches for a substring within a text string 🔍

Conclusion 🎯
This README file provides an overview of some essential DAX functions you can use to work with data in Power BI and other Microsoft tools. By mastering these functions, you can perform a wide range of calculations, manipulate dates, and analyze data efficiently.

Feel free to explore each function and use the examples provided to get started with your DAX journey! 🚀









