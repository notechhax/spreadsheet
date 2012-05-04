spreadsheet
===========

computer engineering assignment
A Simple C++ Spreadsheet
Your task is to design a simple integer spreadsheet consisting of a single column of ten (10) cells. The spreadsheet will display the sum of the cells at the bottom of the column.
Your development should follow these steps:
- Write the code to clear the window and output the title, the menu with the instructions for the use of the spreadsheet, the cell number labels, and the word “SUM” at the bottom of the column of cell numbers.
- Modify your code to also display the values of the 10-element integer array in a column next to the labels, which contains the data of the respective 10 cells. The array elements should be initialized to 10.
- Add code to also have an integer variable named “sum”. The value of this variable will be computed by a function, in which the array is passed into and adds the values of the 10-element array.
- Add the code to position the cursor in the first cell. Add code to allow the user to move the cursor to the cell of their choice by pressing ‘2’ for down or ‘8’ for up. If the cursor reaches the top or bottom cell, it should not be allowed to continue above or below the column.
- Add the code to input new integer values for the cell in which the cursor is located (‘5’ should be the key pressed to select this feature). After the data is entered, the “sum” function should be called to re-compute the sum and adjust the displayed sum. The cursor should then be placed back in the cell it last occupied.
- The user can quit the program at any time by pressing ‘q’.
Your program should be well-documented using the comment feature of C++. Your filename should be “spreadsheet”.
The computer labs are open during all periods. Please make use of your time efficiently.