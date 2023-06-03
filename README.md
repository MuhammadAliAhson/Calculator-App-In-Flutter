# Calculator

This is a basic calculator application built using Flutter. It provides a simple interface for performing arithmetic operations.

## UI
<img width="960" alt="calculator" src="https://github.com/MuhammadAliAhson/Calculator-App-In-Flutter/assets/105967134/57a9514c-d111-4fdd-bd2a-99a4ce65bb22">



## How to Use

1. Ensure you have Flutter installed on your machine.
2. Clone the repository or download the source code files.
3. Open the project in your preferred IDE or editor.
4. Run the `main.dart` file to start the application.

## Features

The calculator supports the following features:

- Addition (`+`)
- Subtraction (`-`)
- Multiplication (`*`)
- Division (`/`)
- Decimal point (`.`)
- Clearing the input (`CLEAR`)
- Calculating the result (`=`)

## Implementation Details

The calculator is implemented using Flutter, a cross-platform UI toolkit for building natively compiled applications. It follows the basic structure of a Flutter application, with a main entry point and a widget hierarchy.

### Widget Structure

The main widget in this application is `SimpleCalculator`, which extends `StatefulWidget`. It represents the entire calculator interface.

The UI is divided into two main sections:

1. Display: It shows the current input/output value of the calculator. It is implemented using a `Text` widget.

2. Buttons: The calculator buttons are organized in a grid layout. Each button is implemented using the `ElevatedButton` widget. The `buildButton` method is used to create these buttons dynamically.

### State Management

The state of the calculator is managed by the `_SimpleCalculatorState` class, which extends `State<SimpleCalculator>`. It holds the current input/output value, the operands, and the selected operator.

The `buttonPressed` method is responsible for handling button presses. It updates the state and performs the corresponding calculations based on the pressed button.

The `setState` method is called to update the UI whenever the state changes, ensuring that the changes are reflected in the user interface.

## References

This code is created by [Muhammad Ali Ahson]. It is intended as a reference implementation of a simple calculator in Flutter. Feel free to use and modify the code according to your needs. If you found this code helpful, please consider providing appropriate attribution.
