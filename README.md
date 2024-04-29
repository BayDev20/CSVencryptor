 ### CSV File Encryption Tool
![CSV Encrypter](https://github.com/BayDev20/CSV-File-Encryptor/assets/152105436/116cbfc1-ef48-4497-b615-461fd5985c93)


The CSV File Encryption Tool is a simple Python application built with Tkinter that allows users to encrypt and decrypt CSV files using a specified key.

## Features

- **Encryption**: Encrypts the contents of a CSV file using Fernet Encryption.
- **Decryption**: Decrypts previously encrypted CSV files using the correct decryption key.
- **Key Validation**: Validates the decryption key before performing decryption to ensure data integrity.
- **User-Friendly Interface**: Provides a graphical user interface (GUI) for easy interaction with the tool.

## Getting Started

### Prerequisites

- Python 3.x installed on your system.

### Installation

1. Clone the repository to your local machine:

   ```sh
   git clone https://github.com/BayDev20/CSV-File-Encryptor.git
   ```
2. Install the required dependencies:
   ```sh
   pip install -r requirements.txt
   ```
### Usage
1. Run the Python script main.py to launch the application:
   ```sh
   python Encrypt.py
   ```
2. Choose a encrpytion key or enter a decryption key then choose the file. If the wrong decrption key is entered an error will appear.

### NOTE
This program creates an encrytped or decrypted copy. It does not alter the original. 
