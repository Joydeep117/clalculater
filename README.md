# Calculator

A modern, responsive calculator web application built with HTML, CSS, and JavaScript.

## Features

- **Basic Operations**: Addition (+), Subtraction (-), Multiplication (×), Division (÷)
- **Advanced Functions**: 
  - Percentage (%)
  - Sign toggle (±)
  - Decimal point support
  - Backspace (⌫)
  - Clear (C)
- **Keyboard Support**: Full keyboard input support for all operations
- **Responsive Design**: Works on desktop and mobile devices
- **Modern UI**: Clean, dark-themed interface with smooth animations

## How to Use

### Opening the Calculator

Simply open `index.html` in any modern web browser:
- Double-click the file on Windows
- Or right-click and select "Open with" your preferred browser

### Mouse/Touch Controls

- Click number buttons (0-9) to input digits
- Click operation buttons (+, -, ×, ÷) to perform calculations
- Click "=" to calculate the result
- Click "C" to clear everything
- Click "⌫" to delete the last digit
- Click "±" to toggle positive/negative
- Click "%" to convert to percentage

### Keyboard Controls

- **Numbers**: `0-9` - Input digits
- **Operations**: `+`, `-`, `*`, `/` - Perform operations
- **Equals**: `Enter` or `=` - Calculate result
- **Clear**: `Escape` - Clear all
- **Backspace**: `Backspace` - Delete last digit
- **Decimal**: `.` - Input decimal point
- **Percent**: `%` - Convert to percentage

## Project Structure

```
calculater/
├── index.html    # Main HTML structure
├── style.css     # Styling and layout
├── script.js     # Calculator logic and functionality
└── README.md     # This file
```

## Browser Compatibility

Works on all modern browsers including:
- Chrome
- Firefox
- Safari
- Edge
- Opera

## Technologies Used

- **HTML5**: Structure and semantic markup
- **CSS3**: Styling with modern features (Grid, custom properties)
- **Vanilla JavaScript**: No dependencies, pure JavaScript implementation

## Features in Detail

### Error Handling
- Division by zero shows "Error"
- Handles edge cases gracefully

### Number Formatting
- Automatically removes trailing zeros
- Supports large numbers
- Proper decimal handling

### State Management
- Tracks current input, previous value, and operator
- Handles chained operations
- Maintains calculation history during operation chains

## License

Free to use and modify for personal or commercial projects.
.........................................................................................................................................................................................................................................

