# File-Encrypter

Project Title: File Encrypter

Description:
The File Encrypter project is a command-line tool designed to encrypt and decrypt files using the Fernet encryption algorithm from the cryptography library in Python. The tool allows users to encrypt their sensitive files to protect their contents from unauthorized access. It utilizes symmetric encryption, where the same key is used for both encryption and decryption, providing a straightforward and efficient way to secure files.

Features:

Key Generation: The tool generates a random encryption key using the Fernet.generate_key() function.
Encryption: Users can encrypt their files by providing the input file path, output file path, and encryption key. The tool reads the contents of the input file, encrypts them using the provided key, and writes the encrypted data to the output file.
Decryption: Encrypted files can be decrypted by providing the input (encrypted) file path, output file path, and encryption key. The tool reads the encrypted data from the input file, decrypts it using the provided key, and writes the decrypted data to the output file.
Key Management: Users can save the generated encryption key to a file for later use and load it when needed for encryption or decryption.
Usage:

To encrypt a file: python file_encrypter.py encrypt input_file.txt encrypted_file.txt
To decrypt a file: python file_encrypter.py decrypt encrypted_file.txt decrypted_file.txt
Technologies Used:

Python
cryptography library (for Fernet encryption)
