# QR Code Generator

This is a simple Python script to generate QR codes. The script takes a URL or any text, encodes it into a QR code, and saves the generated image as a `.png` file.

## Features

- **Customizable**: Set the size, error correction level, and border of the QR code.
- **Simple to Use**: Just specify the link or text you want to encode, and the script will handle the rest.
- **Lightweight**: Only requires a few dependencies.

## Getting Started

### Prerequisites

- Python 3.x
- Required Python libraries listed in `requirements.txt`

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/qr-code-generator.git
    cd qr-code-generator
    ```

2. Install the required Python libraries:

    ```bash
    pip install -r requirements.txt
    ```

### Usage

1. Open the `qr_code_generator.py` file.

2. Replace the `link` variable with the URL or text you want to encode:

    ```python
    link = "https://your-link-here"
    ```

3. Run the script:

    ```bash
    python qr_code_generator.py
    ```

4. The generated QR code will be saved as `qrcode.png` in the current directory.
