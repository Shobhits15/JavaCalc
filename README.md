# JavaCalc 🧮

A simple desktop calculator built with **Java Swing**, supporting basic arithmetic operations through a clean, dark-themed GUI.

## Features

- Standard arithmetic operations: addition, subtraction, multiplication, and division
- Digit buttons (0–9) and decimal point support
- Clear button to reset the display
- Real-time display of input and results
- Custom-styled UI with a black background, colorful operator buttons, and a white display label

## Tech Stack

- **Language:** Java
- **GUI Toolkit:** Java Swing (`JFrame`, `JButton`, `JLabel`)
- **Event Handling:** `ActionListener`

## Prerequisites

- [Java Development Kit (JDK)](https://www.oracle.com/java/technologies/downloads/) 17 or higher installed
- Any Java IDE (IntelliJ IDEA, Eclipse, VS Code) or just the command line

## Getting Started

### Clone the repository

```bash
git clone https://github.com/<your-username>/<your-repo-name>.git
cd <your-repo-name>
```

### Compile and run

```bash
javac Calculator.java
java Calculator
```

## Project Structure

```
JavaCalc/
├── Calculator.java   # Main source file containing the GUI and logic
└── README.md
```

## How It Works

The calculator maintains the current input string and the pending operation internally. When a number button is pressed, the digit is appended to the display. When an operator button is pressed, the current value is stored and the operator is flagged as active. Pressing `=` evaluates the stored value against the new input using the selected operation and displays the result.

## Future Improvements

- Add keyboard input support
- Add support for percentage and square root operations
- Improve error handling for invalid expressions (e.g., division by zero)
- Add unit tests for calculation logic

## License

This project is open source and available under the [MIT License](LICENSE).

## Author
Shobhit..
made with ☕ and Java Swing.