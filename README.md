# Pyramid-Generator-Project
This project generates a pyramid pattern using a specified character. The pyramid's height and whether it is inverted or not can be controlled through variables. The program dynamically calculates the number of spaces and characters required for each row to form the pyramid shape.
![image](https://github.com/user-attachments/assets/e41b51b6-b97a-435f-b570-caf8b9d1f170)

## Features

- **Character Customization:** Allows you to specify the character used to build the pyramid (e.g., `"!"`).
- **Row Count:** You can adjust the number of rows in the pyramid by modifying the `count` variable.
- **Inversion:** The pyramid can be printed in an inverted format by toggling the `inverted` flag.

## Code Walkthrough

The project consists of JavaScript code that performs the following steps:

1. **Variable Initialization:**
   - `character`: Defines the character used for building the pyramid (default is `"!"`).
   - `count`: Specifies how many rows the pyramid should have.
   - `rows`: An array to store each row of the pyramid.
   - `inverted`: A flag to control whether the pyramid is printed normally or inverted.

2. **Padding Function:**
   - `padRow(rowNumber, rowCount)`: A helper function to calculate the spaces before and after the character pattern for each row.

3. **Loop to Build Pyramid:**
   - A loop runs from 1 to `count`, creating a row for each iteration and adding it to the `rows` array.
   - The rows are either added normally or prepended (if inverted) depending on the value of `inverted`.

4. **Result Construction:**
   - A final loop iterates over the rows array and concatenates each row into a string (`result`), which is then printed.

## Example Output

For `count = 5` and the default character `"!"`, the output would be
