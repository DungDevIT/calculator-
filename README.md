# Calculator Project

## Description

This project is a simple web-based calculator built using HTML, CSS, and JavaScript. The calculator performs basic arithmetic operations and features a clean, intuitive user interface.

## Project Structure

The project consists of three main files:

1. **index.html**: The main HTML file that structures the calculator's layout.
2. **styles.css**: The CSS file that styles the calculator's appearance.
3. **script.js**: The JavaScript file that adds functionality to the calculator.

## HTML Structure (index.html)

The HTML file defines the structure of the calculator. It includes:

- A `div` with the class `calculator` that contains the entire calculator.
- An `input` element for the display, which shows the current input and results.
- Several `button` elements arranged in rows, each representing a different calculator function or number.

### Key Sections

- **Display**: An input field (`inputBox`) to display the current number or result. It is disabled to prevent user input directly.
- **Buttons**: Arranged in rows, the buttons include numbers (0-9), operators (+, -, *, /, %), and functions (AC, DEL, plus-minus, equals).

## CSS Styling (styles.css)

The CSS file applies styles to the calculator to enhance its visual appearance. Key styling includes:

- Centering the calculator on the page.
- Defining the size and style of the display and buttons.
- Adding visual feedback for button interactions.

## JavaScript Functionality (script.js)

The JavaScript file provides the functionality for the calculator. It includes:

- Event listeners for button clicks to update the display and perform calculations.
- Functions to handle arithmetic operations, clearing the display, deleting the last input, and toggling the sign of the current input.

## Usage

To use the calculator:

1. Open the `index.html` file in a web browser.
2. Click the buttons to input numbers and operations.
3. The display will show the current input, and results will be displayed when the equals (`=`) button is clicked.

### Buttons

- **Numbers (0-9)**: Input digits into the display.
- **Operators (+, -, *, /, %)**: Perform arithmetic operations.
- **AC**: Clear the display.
- **DEL**: Delete the last input character.
- **±**: Toggle the sign of the current input.
- **.**: Input a decimal point.
- **=**: Calculate and display the result.

## Installation

No installation is required. Simply clone or download the project files and open `index.html` in your preferred web browser.

## Contributing

If you would like to contribute to this project, please fork the repository and submit a pull request with your changes. Ensure your code follows the existing style and includes comments where necessary.

## License

This project is open source and available under the MIT License. You are free to use, modify, and distribute this code as you see fit.

## Acknowledgements

This calculator project was inspired by common web-based calculators and aims to provide a simple, functional example of HTML, CSS, and JavaScript integration.
