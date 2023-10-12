# Password Manager

## Overview

This is a simple command-line password manager written in Python. It allows users to securely store and manage their passwords for different sites and applications.

## Features

- **Secure Encryption**: Passwords are stored securely using AES encryption.
- **Command-Line Interface**: Easy-to-use command-line interface for managing passwords.
- **Database Storage**: Passwords are stored in a local SQLite database.

## Usage

### Prerequisites

- Python 3.x
- Required Python libraries can be installed using the provided `requirements.txt` file.

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/password-manager.git
2. Install the requirements
   ```bash
   pip install -r requirement.txt
### Usage
1. To veiw the saved passwords
   ```bash
   python main.py --view <site>
2. To view all passwords
    ```bash
   python main.py --view *

3. To add new password
    ```bash
   python main.py --insert <site> <username> <password>
4. To update the saved password.
   ```bash
   python main.py --update <site> <username> <new_password>
5. To delete the saved password.
   ```bash
   python main.py --delete <site> <username>
6. To change the  master password.
   ```bash
   python main.py --maskey <old_master_key> <new_master_key>
7. For help
   ```bash
   python main.py -h
   







