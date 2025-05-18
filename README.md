# Random Password Generator

A simple command-line tool that generates secure random passwords of customizable length.

## Description

This Python script creates strong, random passwords using a combination of uppercase letters, lowercase letters, numbers, and special characters. It leverages Python's built-in `random` and `secrets` modules to ensure cryptographic security in the generated passwords.

## Features

-○ Generate passwords of any length
-○ Include a mix of uppercase letters, lowercase letters, numbers, and special characters
-○ Uses cryptographically secure random number generation

## Requirements

-○ Python

## Installation

1. Clone or download this repository to your local machine
2. Ensure you have Python installed

## Usage

Run the script on the command line(terminal):

```
python password_generator.py
```

When prompted, enter your desired password length as a number. The program will generate and display your random password.

## Example

```
$ python password_generator.py
Enter password length: 16
Your password is: Zd7*fP9$kL!2xR@t
```

## Security Information

This password generator uses Python's `random` and `secrets` modules. While the `random` module is used for character selection, the implementation could be made more secure by consistently using the `secrets` module, which is specifically designed for generating cryptographically strong random numbers suitable for security purposes.

## Author

Ashley Motsie 

## Contributions

Contributions, issues, and feature requests are welcome!
