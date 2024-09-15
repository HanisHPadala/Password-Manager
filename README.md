# Password-Manager
<p>This repository features a simple command-line password manager built in Python. It provides functionalities to generate, store, encrypt, decrypt, and retrieve passwords securely. The password manager uses the cryptography library for encryption and JSON files for storing encrypted passwords.

The generate_password function creates a random password of a specified length, with optional inclusion of symbols and numbers. For encryption, the generate_key function generates a secure key using Fernet, which is then saved to a file. The encrypt_password and decrypt_password functions handle the encryption and decryption of passwords using this key.

Passwords are stored in a JSON file, managed by the store_password function, which adds or updates entries with encrypted passwords. The retrieve_password function allows for the retrieval and decryption of these passwords based on the service name. The list_passwords function lists all stored passwords, displaying their service names and encrypted values.

The interactive menu function offers a command-line interface where users can generate passwords, store them, retrieve them, list all stored passwords, or exit the program. It continuously prompts the user for input, providing options to perform each of these actions.

To use this password manager, ensure Python 3.x is installed along with the cryptography library. Install the library using pip install cryptography. Run the script to interact with the menu and manage your passwords securely. Contributions and suggestions are welcome,</p>
