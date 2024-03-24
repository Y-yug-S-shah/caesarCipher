# caesarCipher
The Caesar Cipher is a simple substitution cipher where each letter in the plaintext is shifted a certain number of positions down the alphabet. This code allows you to encrypt and decrypt messages using this technique.

# functionality:

The caesar_cipher function takes two arguments:
text: The text string to be encrypted or decrypted.
shift: The shift value (positive for encryption, negative for decryption).
The function iterates through each character in the text and performs the following:
Checks if the character is alphabetical.
If it is, it calculates the shifted character based on the shift value and base value ('A' for uppercase, 'a' for lowercase).
It handles wrapping around the alphabet (e.g., 'X' shifted by 3 becomes 'A').
Non-alphabetical characters are left unchanged.
The main function prompts the user for the message and shift value.
It then calls the caesar_cipher function for encryption and decryption.
Finally, it prints the encrypted and decrypted messages.
