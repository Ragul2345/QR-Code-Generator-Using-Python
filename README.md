## 📌 QR Code Generator Using Python ##

# Project Description

This project demonstrates how to generate a QR code using Python.
The QR code stores a simple text message and saves it as an image file.
The project is beginner-friendly and helps in understanding how external Python libraries are used for real-world applications.

# Objectives

To learn how to use Python libraries
To generate QR codes programmatically
To understand how data is encoded into QR codes
To save QR codes as image files

# Technologies Used

Programming Language: Python 3
Library: qrcode
Tool: Command Prompt / VS Code

# Requirements

Python 3.x installed on the system
qrcode and Pillow libraries

# Explanation of the Code

import qrcode → Imports the QR code library
data → Stores the text to be encoded
QRCode() → Creates a QR code object with custom size and error correction
add_data() → Adds text to the QR code
make() → Generates the QR code
make_image() → Creates the QR image
save() → Saves the image as a PNG file

# How to Run

1. Install the required libraries using pip.
2. Run the Python file using `python qr_code.py`.

# Output

The program generates an image file named qr_code.png.
When scanned using Google Lens or mobile camera, it displays the encoded text message.
