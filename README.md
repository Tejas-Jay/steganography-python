# Steganography-Python

## Project Overview

Secure Data Hiding In Images - A Python Implementation of Steganography: This project utilizes image processing techniques to securely embed sensitive information within seemingly ordinary images, enhancing data privacy and security.
This project can be used in demonstrating how to embed secret messages within images for covert communication.

## Requirements

- Python 3.x
- OpenCV (cv2) library: `pip install opencv-python`

## Usage

1. **Run the Script:**
   - Execute the Python script.
2. **Prepare Your Image:**
   - Select the required image from the pop-up window.
3. **Enter Message and Passcode:**
   - The script will prompt you to enter your secret message and a passcode.
4. **Encryption:**
   - The script will prompt you to enter the name you want for the encrypted image.
   - The message is encrypted and embedded within the image.
   - An encrypted image with the name given by you "given_name.jpg" will be saved.
5. **Decryption:**
   - The script will prompt you to enter the same passcode used during encryption.
   - If the passcode matches, the script will decrypt the message and display it.

