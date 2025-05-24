# PRODIGY_CS_02

Simple Image Encryption Tool
Overview
This is a Python-based tool that performs simple image encryption and decryption using pixel manipulation. It applies an XOR operation on the RGB values of each pixel with a user-provided key (0-255). The tool is designed for educational purposes to demonstrate basic image processing and encryption concepts using the PIL (Pillow) library.

Features

Encrypts or decrypts images by applying an XOR operation on RGB pixel values with a user-specified key.
Supports common image formats (e.g., JPG, PNG) via the Pillow library.
Simple command-line interface for ease of use.
Validates user input for mode, image paths, and encryption key.

Requirements

Python 3.6+
Pillow library (pip install Pillow)

Installation

Clone this repository:git clone https://github.com/Dhilip-7/PRODIGY_CS_02/image-encryption-tool.git
cd image-encryption-tool


Install the required dependency:pip install Pillow



Usage
Run the script and follow the prompts to encrypt or decrypt an image.
Example Commands

Encrypt an image:
python image_encryption.py

Then:

Choose mode: 1 (Encrypt)

Enter input image path: input.jpg

Enter output image path: encrypted.jpg

Enter encryption key: 42 (a number between 0 and 255)



Decrypt an image:

python image_encryption.py

Then:

Choose mode: 2 (Decrypt)

Enter input image path: encrypted.jpg

Enter output image path: decrypted.jpg

Enter encryption key: 42 (must match the key used for encryption)



Output Example
Image Encryption/Decryption Tool
--------------------------------
Choose mode:

1. Encrypt
   
2. Decrypt
   
Enter mode (1/2): 1

Enter input image path (e.g., input.jpg): input.jpg

Enter output image path (e.g., output.jpg): encrypted.jpg

Enter encryption key (0-255): 42

Encrypted image saved as encrypted.jpg


Notes

Key: The encryption key must be a number between 0 and 255 (inclusive) due to the 8-bit RGB value range.

Reversibility: The same key used for encryption must be used for decryption to restore the original image.

Image Formats: Ensure the input image is in a format supported by Pillow (e.g., JPG, PNG).
