# Image Encryption Project

This project implements a system for encrypting image files using the Go programming language. The objective is to protect image files through encryption, utilizing the AES algorithm and a password provided by the user.

## Features
- **Image Encryption**: Allows users to encrypt image files using a password.
- **Image Decryption**: Enables users to decrypt encrypted image files with the correct password.
- **Command-Line Interface**: Simple command-line interface for user interaction.

## Technologies Used
- Go (Golang)
- AES (Advanced Encryption Standard)
- PBKDF2 (Password-Based Key Derivation Function 2)

## Prerequisites
- Install Go from [here](https://golang.org/dl/).

## How to Run the Project
1. Clone the repository:
   ```bash
   git clone <repository_URL>
   cd <repository_name>

2. Install dependencies (if necessary):
    go mod tidy

3. To encrypt an image:
    go run main.go encrypt <image_path>

4.To decrypt an image:
    go run main.go decrypt <image_path>

5. Enter your password when prompted.

Project Structure
    main.go: Contains the encryption and decryption logic.
    filecrypt: Package implementing the encryption and decryption functions.

Usage Example
# Encrypt an image
go run main.go encrypt img.jpeg
Enter password:
Confirm password:
Encrypting...
File successfully protected

# Decrypt the image
go run main.go decrypt img.jpeg
Enter password:
Decrypting...
File successfully decrypted

Contributions
Contributions are welcome! Fork the repository and submit a pull request.

License
This project is licensed under the MIT License. See the LICENSE file for details.


### Personalize
- **Replace `<repository_URL>`** and `<repository_name>` with your actual GitHub repository link and name.
- Feel free to adjust the content as needed or add any additional sections specific to your project. 







