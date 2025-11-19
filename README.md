📌 Currency Converter – Flutter App
📖 Overview

The Currency Converter is a simple and user-friendly Flutter application designed to convert an amount from USD to INR.
It takes input from the user, multiplies it by a fixed conversion rate (80 INR per USD), and displays the converted result instantly.

This project demonstrates:

Flutter Stateful Widgets

Managing user input with TextEditingController

Updating UI using setState()

Designing UI with Material widgets

Basic currency conversion logic

✨ Features

Enter USD amount in a text field

Convert USD → INR with a single button click

Displays output in real-time

Clean UI with responsive layout

Error-free handling for numeric input

🧠 How It Works

User enters an amount in USD

On pressing Convert, the app executes:

INR = USD × 80


The converted result is shown on the screen

🛠 Technologies Used

Flutter

Dart

Material Design Widgets

StatefulWidget

TextEditingController

📂 Project Structure
lib/
 └── currency_converter.dart

📸 Output (Screenshot Description)

Shows a bold INR result text

A text field with hint "Please enter the amount in USD"

A "Convert" button in black theme

🚀 How to Run

Install Flutter SDK

Run the command:

flutter pub get


Execute the app:

flutter run

