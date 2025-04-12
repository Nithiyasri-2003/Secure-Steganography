# Secure-Steganography

## Overview
This project implements **image steganography** where data (text or binary) is hidden inside an image using encryption and decryption methods. The project uses algorithms like **RSA** and **AES** for encrypting the data before embedding it in the image.

## Project Features:
- **Encryption**: Data is encrypted using RSA and AES encryption algorithms.
- **Steganography**: Hidden data is embedded in the image using the least significant bit (LSB) method.
- **Decryption**: The encrypted data can be extracted from the image and decrypted back to its original form.
  
## Tools & Technologies Used:
- **Python**: For implementing the encryption, decryption, and steganography algorithms.
- **Pillow**: Python Imaging Library (PIL) used for handling images.
- **Cryptography Libraries**: Used for RSA and AES encryption and decryption.

## How It Works:
1. **Encryption**: The text or binary data is encrypted using RSA or AES.
2. **Steganography**: The encrypted data is embedded in an image using the Least Significant Bit (LSB) method.
3. **Extraction**: The hidden data is extracted from the image.
4. **Decryption**: The extracted encrypted data is decrypted back to its original form.

## How to Run:
1. Clone this repository to your local machine:
2. Install the required libraries:
3. Run the `steganography.py` script to hide data in an image and extract it.



## File Structure:
- **steganography.py**: Python script for embedding and extracting data from images.
- **encryption.py**: Python script for RSA and AES encryption.
- **images/**: Folder containing sample images (original, steganographed, and extracted images).
- **requirements.txt**: List of required Python libraries.

## Contributing:
Feel free to fork this project, open issues, or create pull requests to improve the project. Contributions are welcome!



