# Caesar Cipher Python Program

## Description

This Python program implements a simple version of the Caesar Cipher, a type of substitution cipher where each letter in the plaintext is shifted a certain number of places down or up the alphabet. The program allows users to encode (encrypt) or decode (decrypt) messages using this cipher technique.

## Features

- Encryption and Decryption: Users can choose to either encrypt or decrypt a message.
- Custom Shift Values: Users can specify the shift value for the cipher.
- Continuous Operation: The program can continuously process messages until the user decides to stop.

## How to Use

- Start the Program: Run the program in a Python environment.
- Choose Operation: When prompted, type 'encode' to encrypt a message or 'decode' to decrypt a message.
- Enter the Message: Type the message you want to encrypt or decrypt. Note that the current version of the program only processes lowercase alphabetic characters.
- Enter Shift Value: Enter an integer value for the shift. The program will automatically adjust shift values greater than 26.
View the Result: The program will display the encoded or decoded message.
- Repeat or Exit: After processing a message, you can choose to encode/decode another message or exit the program by typing 'yes' to continue or 'no' to stop.

## Dependencies

- Python Standard Library: No external libraries are required as the program uses only the Python Standard Library.
- Art Module: The art module is used to print a logo at the start of the program. Ensure this module is installed (pip install art) or remove the print(logo) line if the module is unavailable.

## Disclaimer

This program is for educational purposes only. The Caesar Cipher is a basic encryption method and should not be used for securing sensitive data.
