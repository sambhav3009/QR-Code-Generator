# QR Code Generator 🖼️➡️📲

This Python project generates a QR code from a given URL or text. The generated QR code can be scanned with any QR code reader, making it easy to share links, contact information, or any other text-based data.

## Table of Contents
- [Features](#features)
- [How It Works](#how-it-works)
- [Requirements](#requirements)

## Features

- Creates a QR code from any text or URL.
- Saves the generated QR code as a PNG file for easy sharing.
- Customizable QR code size.

## How It Works

1. **Data Input**:
   - The script takes a URL or any text input and converts it into a QR code.
2. **QR Code Generation**:
   - Using the `pyqrcode` module, the script encodes the input data into a QR code.
3. **Save as PNG**:
   - The QR code is saved as a PNG file, allowing you to share or print the code as needed.

## Requirements

- Python 3.x
- Install the following Python packages:
   ```bash
   pip install pyqrcode pypng
