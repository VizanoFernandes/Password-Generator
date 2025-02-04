# Password-Generator
This Python script generates secure random passwords based on user-defined lengths. It uses recursion to build a password character by character, ensuring the desired length is met. The program continuously prompts the user for input, allowing multiple password generations until the user chooses to exit.

Features;

Generates passwords with a user-defined length.

Utilizes all printable characters, maximizing randomness and complexity.

Provides an interactive command-line interface.

Includes error handling for invalid inputs.


How It Works;

The user enters the desired password length.

The stretch function recursively builds the password by appending random characters.

The script generates and displays the password or exits if the user inputs "e".
