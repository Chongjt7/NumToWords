# Number to Words Converter (Visual Studio MVC .NET)

## Table of Contents

- [Description](#description)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Testing](#testing)
- [Contributing](#contributing)
- [License](#license)

## Description

This web application, built using Visual Studio MVC .NET, converts decimal numbers into words. It provides a simple interface for users to input decimal numbers and receive their equivalent representation in words.

## Features

- Supports decimal numbers with up to two decimal places.
- Handles large numbers using BigInt for precision.
- Provides a user-friendly interface for easy interaction.

## Installation

1. Clone this repository to your local machine:
git clone <repository_url>

2. Open the solution file (`NumberToWordsConverter.sln`) in Visual Studio.

3. Build the solution by selecting `Build > Build Solution` from the menu.

## Usage

1. Run the application by pressing `F5` or selecting `Debug > Start Debugging` from the menu.

2. Visual Studio will launch the application in your default web browser.

3. Once the web application is loaded in your browser, you'll see an input field where you can enter a decimal number.

4. Enter a decimal number and click the "Submit" button.

5. The application will display the equivalent representation of the number in words.

## Testing

You can test the functionality of the application using the provided test cases:

1. **Valid Input**: Enter a valid decimal number and verify the displayed output.
2. **Zero Input**: Enter zero and ensure the output is "zero dollars."
3. **Negative Input**: Enter a negative number and verify the output contains "negative."
4. **Large Input**: Enter a large number and ensure accurate conversion.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvement, please open an issue or create a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
