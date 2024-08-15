# Colorful Calculator 

## Project Overview

The **Colorful Calculator** is a simple, responsive calculator web application built using HTML, CSS, and JavaScript. It allows users to perform basic arithmetic operations, such as addition, subtraction, multiplication, and division, with a visually appealing and user-friendly interface.

### Features:
- **Responsive Design**: The calculator adjusts to different screen sizes.
- **Basic Arithmetic Operations**: Perform addition, subtraction, multiplication, and division.
- **Error Handling**: If an invalid operation is attempted, an error message is displayed.
- **Clear Function**: Easily reset the calculator using the 'C' button.

---

## Project Structure:

### HTML:
The `index.html` file defines the structure of the calculator interface:
- **Input Display**: A disabled text input field (`#display`) to show the current value or result.
- **Buttons**: Calculator buttons organized in a grid layout, including number buttons (0-9), operators (`+`, `-`, `*`, `/`), and a clear (`C`) button.
- **JavaScript file (`script.js`)** linked for interactivity.

### CSS:
The `styles.css` file manages the layout and style:
- **Calculator Layout**: The calculator is centered on the screen with a minimal, modern design.
- **Button Design**: Buttons are styled with a consistent color scheme, rounded corners, and hover/active states for user feedback.
- **Responsive Grid**: Buttons are arranged in a 4x4 grid using CSS Grid, ensuring equal spacing and size.

### JavaScript:
The `script.js` file contains the logic for the calculator's functionality:
- **Display Update**: Functions to append values to the display when buttons are pressed.
- **Clear Function**: A function to clear the display when the 'C' button is pressed.
- **Calculate Function**: Uses `eval()` to compute the entered expression. Errors are handled by displaying "Error" if the input is invalid.

---

## Project Breakdown:

### 1. **Display**:
- The calculator display is an input field that shows the user's input and the result of calculations. It is disabled so that the user cannot manually type in values.

### 2. **Button Functions**:
- **`appendToDisplay(value)`**: Appends the pressed button's value (numbers, operators) to the display.
- **`clearDisplay()`**: Clears the current value on the display.
- **`calculate()`**: Evaluates the entered expression and updates the display with the result. If the input is invalid, it displays an error.

### 3. **Styling**:
- The calculator has a clean and modern design with blue buttons for numbers and operators, and red buttons for the `C` and `=` buttons.
- Buttons change color when hovered or pressed to enhance the user experience.

---

## How to Run the Project:

### 1. Clone the Repository:
```bash
git clone https://github.com/your-repo-name.git
```

### 2. Open the Project:
Open the `index.html` file in any modern web browser to view and use the calculator.

### 3. File Structure:

```
/Colorful-Calculator
│
├── index.html       # Main HTML file
├── styles.css       # CSS file for styling the calculator
├── script.js        # JavaScript file for calculator functionality
└── README.md        # This readme file
```

### 4. Usage:
1. Open the `index.html` file in a browser.
2. Use the calculator to perform basic arithmetic by clicking the number and operator buttons.
3. Press the `=` button to calculate the result, or press the `C` button to clear the display.

---

## Customization:

1. **Color Scheme**: Change the button colors in the CSS file by modifying the `button` and `.operator` classes.
2. **Button Layout**: Adjust the grid layout or add more advanced buttons (e.g., square root, percentage) by modifying the HTML and CSS files.
3. **Functionality**: Expand the JavaScript code to include more complex operations or improve the error handling.

---

## Credits:
This project is created using basic web technologies:
- **HTML** for the structure.
- **CSS** for styling.
- **JavaScript** for the functionality and interactivity.

---

### License:

This project is licensed under the MIT License. You are free to use, modify, and distribute this project for personal or educational purposes.
