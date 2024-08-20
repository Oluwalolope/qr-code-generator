# QR Code Generator

## Overview

This is a simple QR Code Generator built with Node.js. It allows users to input a URL, and it will generate a QR code image (`.png`) and save it to the local system. Additionally, it logs the input URL to a text file. This project is perfect for those looking to quickly generate QR codes from URLs.

## Features

- Generates a QR code image from a user-provided URL.
- Saves the generated QR code as a `.png` file on your local system.
- Logs the provided URL to a text file for future reference.
- Safe and secure: the URL is typed by the user, ensuring that no malicious data is written to your system.

## Installation

1. Clone this repository to your local machine:

    ```bash
    git clone https://github.com/Oluwalolope/qr-code-generator.git
    ```

2. Navigate to the project directory:

    ```bash
    cd qr-code-generator
    ```

3. Install the necessary dependencies:

    ```bash
    npm install
    ```

## Usage

1. Run the application:

    ```bash
    node index.js
    ```

2. You will be prompted to enter a URL in the terminal:

    ```bash
    Please enter a URL to generate a QR code:
    ```

3. After entering the URL, a QR code will be generated and saved as a `.png` file in the project directory. The URL will also be logged in a text file for your records.

## Security Note

This code does not write any malicious data to your system. All URLs are user-provided, ensuring full control over the input and output.

## Contributing

Feel free to contribute to this project by forking the repository and submitting a pull request. All contributions are welcome!

## Contact

If you have any questions or issues, please open an issue in the repository or contact me directly via email at `lopeadeleye@outlook.com`.
