

# Java Swing Calculator

A simple calculator application built using Java Swing. The calculator supports basic arithmetic operations with a clean UI inspired by modern calculator apps.

## Features

* Basic operations: Addition, Subtraction, Multiplication, Division
* Extra functions:

  * AC – Clear all
  * +/- – Toggle sign
  * % – Percentage
  * √ – Square root (button added, implementation pending)
* Decimal input support
* Responsive UI with styled buttons (dark mode inspired)

## Preview

(You can add a screenshot of the calculator window here once you run it and take one)

## Project Structure

```
CalculatorApp
 ┣ App.java          // Entry point
 ┗ Calculator.java   // UI and logic
```

## How to Run

### 1. Compile

```bash
javac App.java Calculator.java
```

### 2. Run

```bash
java App
```

## Requirements

* Java 8 or later
* Any OS (Windows, macOS, Linux)

## Known Issues / TODO

* √ button is in UI but not yet implemented
* String comparison uses == instead of .equals(), which may cause unexpected behavior
* Division by zero not handled gracefully

## Contributing

Pull requests are welcome. If you’d like to add more operations (for example power, memory functions, history), feel free to contribute.

## License

This project is open source under the MIT License.

