# PRODIGY_CS_01

# Caesar Cipher Encryption/Decryption Tool

## Description
This Python script implements a simple Caesar Cipher encryption and decryption tool. The Caesar Cipher is a type of substitution cipher in which each letter in the plaintext is shifted a certain number of places down or up the alphabet. This script allows users to encrypt and decrypt messages using a specified shift value.

## Features
- Encrypt Messages: Converts a plaintext message into ciphertext by shifting each letter by a specified number of positions.
- Decrypt Messages: Converts a ciphertext message back into plaintext by reversing the shift.
- Interactive Interface: Provides a user-friendly command-line interface for choosing between encryption, decryption, or quitting the program.

## How It Works
- Encryption: Each letter in the input text is shifted by the specified number of positions in the alphabet. Non-alphabetic characters remain unchanged.
- Decryption: The encrypted text is shifted back by the same number of positions to retrieve the original message.
- Shift Value: The script supports a shift value between 0 and 25.

## Code Explanation
1. caesar_cipher_encrypt(text, shift):
   - Encrypts the input text by shifting each letter by the specified shift value.
   - Handles both uppercase and lowercase letters.
   - Non-alphabetic characters remain unchanged.

2. caesar_cipher_decrypt(text, shift):
   - Decrypts the input text by shifting each letter back by the specified shift value.
   - Calls the caesar_cipher_encrypt function with a negative shift value.

3. main():
   - Provides an interactive interface for the user to choose between encryption, decryption, or quitting the program.
   - Prompts the user to enter the message and shift value.
   - Displays the encrypted or decrypted message based on user choice.

## Usage
1. Clone the Repository:
   ```bash
   git clone https://github.com/Mohansaikrishna1601/PRODIGY_CS_01.git
   cd PRODIGY_CS_01

2. Run the Script:
   ```bash
   python Caesar\ Cipher.py

3. Follow the Prompts:
    Choose whether to encrypt, decrypt, or quit.
    Enter your message and the shift value.
    View the encrypted or decrypted message.

Example:
Caesar Cipher Program
Would you like to (E)ncrypt, (D)ecrypt, or (Q)uit? E
Enter your message: Hello, World!
Enter the shift value (0-25): 3
Encrypted message: Khoor, Zruog!

Requirements
    Python 3.x

Author
    Mohan Sai Krishna G M
