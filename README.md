# 📱 QR Code Generator

This is a simple Python script to generate a QR code from a given URL. The generated QR code is saved as an SVG file.

## Features ✨

- 🔗 Convert any URL into a QR code.
- 🖼️ Save the QR code as an SVG file.
- 🛠️ Easy to use and minimal setup.

## Requirements 📦

To run this project, you'll need the following Python package installed:

- `pyqrcode`: A Python library to generate QR codes.

## Installation 🚀

Follow these steps to get the QR Code Generator up and running on your local machine.

1. **Clone the repository:**

    ```bash
    git clone https://github.com/yourusername/qr-code-generator.git
    cd qr-code-generator
    ```

2. **Create a virtual environment (Optional but recommended):**

    It's recommended to use a virtual environment to manage dependencies.

    ```bash
    python3 -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install dependencies:**

    Install the necessary Python package:

    ```bash
    pip install pyqrcode
    ```

## Usage 🎨

1. Run the script:

    ```bash
    python qrcode_generator.py
    ```

2. Enter the URL when prompted:

    ```bash
    Enter url to generate QR code: https://example.com
    ```

3. The QR code will be generated and saved as `qrcode.svg` in the current directory.

## Example 📸

After running the script and entering a URL, you will get an SVG file with a QR code that looks like this:

