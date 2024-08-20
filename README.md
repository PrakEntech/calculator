# Flutter Calculator App

A simple, elegant calculator application built using Flutter. This app demonstrates the basic usage of Flutter widgets, state management, and custom UI design. The calculator supports basic arithmetic operations and features a clean, user-friendly interface.

## Features

- **Basic Arithmetic Operations**: Perform addition, subtraction, multiplication, and division.
- **Clear Button**: Reset the calculator to its initial state.
- **Toggle Sign**: Switch between positive and negative values.
- **Percentage Calculation**: Easily calculate percentages.
- **Decimal Support**: Perform calculations with decimal numbers.
- **Responsive UI**: Designed to work seamlessly on different screen sizes.

## Getting Started

### Prerequisites

- Ensure you have [Flutter](https://flutter.dev/docs/get-started/install) installed on your system.
- A suitable IDE (e.g., [Android Studio](https://developer.android.com/studio), [Visual Studio Code](https://code.visualstudio.com/)) for Flutter development.

### Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/yourusername/flutter-calculator.git
   ```

2. Navigate to the project directory:

   ```bash
   cd flutter-calculator
   ```

3. Fetch the dependencies:

   ```bash
   flutter pub get
   ```

4. Run the app:

   ```bash
   flutter run
   ```

## Code Overview

### Main Structure

- **`main.dart`**: The entry point of the application. Contains the main structure of the app and manages the state of the calculator.

### Key Components

- **`MyApp`**: The root widget of the application. It initializes the `MaterialApp` and sets the home screen to the `Calculator` widget.
- **`Calculator`**: A `StatefulWidget` that maintains the state of the calculator, including the current display value and the logic for performing calculations.
- **`calcbutton`**: A custom widget that represents the buttons on the calculator. It uses `ElevatedButton` to provide a rounded, clickable interface.

### Calculator Logic

The calculator logic is handled within the `_CalculatorState` class. It keeps track of the operands and operators, and performs the appropriate calculations based on the user's input. The results are dynamically updated on the display as the user interacts with the buttons.

### UI Design

The UI is designed to mimic a physical calculator with a dark theme. The buttons are arranged in a grid layout, with special styling for the zero button to make it wider and more accessible.

## Customization

You can customize the following aspects of the app:

- **Button Colors**: Modify the button colors by changing the `btncolor` parameter in the `calcbutton` function.
- **Display Style**: Adjust the text style of the display by modifying the `TextStyle` in the `Text` widget inside the `build` method.
- **Additional Features**: Extend the app by adding more advanced operations like square roots, exponentiation, or memory functions.

## Screenshots

Include some screenshots of your app here to showcase the interface and functionality.
