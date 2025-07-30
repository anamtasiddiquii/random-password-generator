# random-password-generator
A simple Python script to generate secure, customizable passwords using random letters, digits, and symbols. It uses the random and string modules to create strong passwords based on user-defined character counts. Great for quick, secure password creation from the command line.

🔐 Random Password Generator in Python
A random password generator is a simple program that creates secure, random passwords by combining letters, digits, and symbols. Using Python’s built-in random and string modules, you can:

Let the user choose how many letters, digits, and symbols they want.

Use:

string.ascii_letters for A–Z and a–z

string.digits for 0–9

A custom string like "@#$*/_" for symbols

Use random.choices() to pick random characters from each group.

Combine all characters, shuffle them, and use ''.join() to make a final password string.
