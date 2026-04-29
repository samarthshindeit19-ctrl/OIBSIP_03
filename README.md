**Password Generator**

A simple and customizable Python script that generates secure random passwords.
The user can specify the password length and choose whether to include letters, numbers, and/or symbols.

**Features**

Choose password length
Optionally include:

 1.Uppercase and lowercase letters
 
 2.Numbers (0–9)
 
 3.Symbols (special characters such as !@#$%)
 
 4.Prevents empty character selection (shows an error if no character type is chosen)

**How It Works**

The script combines the selected character sets using Python’s built-in string module.

It randomly selects characters from that combined set using random.choice().

It outputs a password of the specified length.

**Requirements**

Python 3.6+

No external libraries are required — everything uses Python’s standard library.

**Usage**

Run the script in a terminal

python generate_passwords.txt

Then follow the prompts:


=== Password Generator ===

Enter password length: 12

Include letters? (y/n): y

Include numbers? (y/n): y

Include symbols? (y/n): n

Generated Password: Ab93fKgmXsdE

**Notes**

If you don’t select any character types, the program will display an error message:

Error: No character types selected!

**License**

This project is released under the MIT License — free for personal and commercial use.
