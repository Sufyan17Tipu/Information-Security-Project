# Information-Security-Project
This projects consist of ciphering the text and make it safe

# Encryption & Decryption Tool

This is a simple Python command-line application that implements several classical encryption and decryption algorithms. Users can choose a cipher from the menu, enter the required key(s), and perform either encryption or decryption.

## Available Ciphers
- Additive (Caesar) Cipher
- Multiplicative Cipher
- Affine Cipher
- Hill Cipher
- Vigenère Cipher
- Rotor Cipher
- Keyed Transposition Cipher

## How the Code Works

- `menu()` – Displays the list of available ciphers.
- `get_choice()` – Takes the user's menu selection.
- `additive_cipher()` – Encrypts/Decrypts using a fixed character shift.
- `multiplicative_cipher()` – Uses multiplication modulo 26 for encryption/decryption.
- `affine_cipher()` – Combines multiplication and addition modulo 26.
- `hill_cipher()` – Encrypts text using matrix multiplication.
- `vigenere_cipher()` – Uses a keyword to shift each letter differently.
- `rotor_cipher()` – Applies multiple character shifts to simulate a simple rotor machine.
- `keyed_transposition_cipher()` – Rearranges characters based on a keyword.
- `main` – Runs the menu in a loop, accepts user input, calls the selected cipher function, and displays the result.

## Run the Program

```bash
python main.py
```
