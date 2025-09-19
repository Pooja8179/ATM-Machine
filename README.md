This is a simple ATM Machine Simulation built using Core Java. The project demonstrates fundamental Object-Oriented Programming (OOP) concepts such as interfaces, classes, methods, encapsulation, and user interaction through the console.

The ATM system allows a user to:

🔑 Authenticate with an ATM number and PIN

💰 View available balance

➖ Withdraw money (with balance validation)

➕ Deposit money

📜 View a mini-statement of recent transactions

🚪 Exit the system safely

🛠️ Tech Stack

Language: Java (Core Java, OOP concepts)

Tools: Command Prompt / Terminal

IDE (Optional): VS Code, Eclipse, or IntelliJ IDEA

📂 Project Structure

AtmMain.java → Entry point of the program, handles user interaction

AtmOperationInterf.java → Interface defining ATM operations

AtmOperationImpl.java → Implementation of ATM operations (balance, withdraw, deposit, statement)

Atm.java → Model class for storing transaction details

🚀 How to Run

Clone or download the repository

Open a terminal in the project folder

Compile the Java files:

javac *.java


Run the program:

java AtmMain


Use the default login:

ATM Number: 12345

PIN: 2005

🌟 Features Demonstrated

Java Interfaces & Implementation

Encapsulation of ATM data

Exception handling (invalid inputs, insufficient funds)

Interactive console-based application

Simple Banking operations simulation

📌 Future Enhancements

Add multiple user accounts

Store transactions in a database or file

GUI-based ATM system using JavaFX or Swing

Integration with real banking APIs (for advanced learning)
