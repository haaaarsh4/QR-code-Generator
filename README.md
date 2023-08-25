# QR Code Generator

The QR Code Generator is a Python script that allows you to generate QR codes for URLs. It utilizes the `qrcode` library to create QR codes and the `PIL` (Python Imaging Library) module to manipulate and save the generated QR code image as a PNG file.

## Features

- Generate QR codes for URLs.
- Customize QR code version, error correction level, box size, and border.
- Save the generated QR code as a PNG image.

## Usage Instructions

1. **Install Dependencies**: Before using the QR Code Generator, you need to install the required libraries. Open your terminal and run the following command:
   
   ```bash
   pip install qrcode[pil]
   ```

2. **Customize QR Code Generation**:
   - Open the Python script named `generate_qr_code.py`.
   - Locate the line with `qr.add_data("https://stackoverflow.com/questions/32772596/pip-install-pil-fails")` and replace the URL with the desired link you want to create a QR code for.
   - Adjust the `version`, `error_correction`, `box_size`, and `border` parameters according to your preferences.

3. **Generate QR Code**:
   - Run the Python script you've customized. This will generate the QR code image based on the provided URL and settings.
   - The generated QR code image will be saved as `generatedQR.png` in the same directory as the script.

4. **Utilize the Generated QR Code**:
   - Once the QR code is generated, you can use it for various purposes, such as sharing URLs or adding them to printed materials.

## Additional Notes

- The URL specified in the `qr.add_data()` line determines the content of the generated QR code.
- The `qr.make_image()` function is responsible for creating the QR code image with customizable fill and background colors.

Feel free to adapt and enhance the script as needed to match your specific requirements or integrate it into your projects. Enjoy generating QR codes using the QR Code Generator script!
