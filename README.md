# My Calculator Project

## Overview

This project is a simple web-based calculator that allows users to perform basic arithmetic operations such as addition, subtraction, multiplication, and division. It features a clean interface with a display area and buttons for each digit, operation, and functionality like clear and calculate.

## Features

- **Basic Operations**: Perform addition (+), subtraction (-), multiplication (*), and division (/).
- **Clear Function**: Reset the calculator display and current operation with a clear (C) button.
- **Immediate Execution**: Operations are performed immediately when the equals (=) button is clicked.
- **Responsive Design**: The calculator is usable on various devices with different screen sizes.

## How to Use

1. Open the `index.html` file in a web browser to start the calculator.
2. Click on the buttons to input numbers and operations.
3. Use the 'C' button to clear the current input.
4. Click the '=' button to calculate and display the result.

## Code Structure

The calculator's functionality is implemented using inline JavaScript within the HTML file. Here's a brief overview of the code structure:

- **HTML**: Contains the structure of the calculator, including the display and buttons.
- **CSS**: (Linked as `style.css`) Styles the calculator, including the layout of buttons and display.
- **JavaScript**: Defines the behavior of the calculator, handling button clicks and calculations.

## Security Note

The use of `eval()` in JavaScript is potentially dangerous as it can execute arbitrary code. It's used here for simplicity, but in a production environment, a safer alternative should be implemented to parse and calculate the input.

## Future Improvements

- Refactor the JavaScript code to separate it from the HTML and improve maintainability.
- Replace `eval()` with a safer calculation method.
- Enhance the UI with additional features like keyboard input support and history of calculations.

## Conclusion

This calculator project serves as a basic introduction to web development with HTML, CSS, and JavaScript. It demonstrates how to create a simple interactive web application.
