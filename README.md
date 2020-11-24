# Password_Generator
A Python application that generates a password and checks it against other common passwords.

This password generator will take an input of preferred words and numbers from the user and concatenate them to build a password for the user.

The application will then generate a password and check it against a list of known compromised passwords found from this repository: 
https://github.com/danielmiessler/SecLists

If the generated password is safe, it will return it to the user. If not, it will generate another password. 
