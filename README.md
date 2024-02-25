# ATM Project

## Overview

The ATM project is a Java-based application that simulates the functionalities of an Automated Teller Machine (ATM). It allows users to perform various banking operations such as withdrawal, deposit, balance inquiry, pin change, and generating a mini statement.

## Features

- **User Authentication**: Validates user credentials including card number and PIN.
- **Multiple Bank Support**: Supports different types of debit cards including SBI, HDFC, Axis, and Operator cards.
- **Operator Mode**: Allows authorized operators to perform maintenance tasks such as checking ATM machine balance, depositing cash, resetting user PIN attempts, and viewing activities.
- **Exception Handling**: Custom exceptions are implemented to handle errors such as invalid card, incorrect PIN, insufficient balance, etc.
- **Activity Logging**: Records all activities performed on the ATM machine for auditing purposes.

## Project Structure

The project consists of the following main components:

1. **operation package**: Contains classes responsible for handling ATM operations including user authentication, validation, transaction processing, and operator mode functionalities.
2. **Interfaces**: Defines interfaces such as `IATMServices` for implementing common ATM functionalities.
3. **customException package**: Contains custom exception classes for handling specific error scenarios.
4. **card package**: Contains classes for different types of debit cards including SBI, HDFC, Axis, and Operator cards.

## Getting Started

To run the ATM project:

1. Ensure you have Java Development Kit (JDK) installed on your system.
2. Clone the project repository to your local machine.
3. Open the project in your preferred Java IDE.
4. Compile and run the `ATMOperations.java` file.

## Usage

1. **Insert Card**: Insert your debit card into the ATM machine.
2. **Enter PIN**: Enter your PIN number when prompted.
3. **Select Operation**: Choose from available options such as withdrawal, deposit, balance inquiry, pin change, or mini statement.
4. **Follow Prompts**: Follow on-screen prompts to complete the selected operation.
5. **Terminate Session**: When done, choose to exit the session.

## Contributors

- [Kiran rajput](https://github.com/iamkiranrajput)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
