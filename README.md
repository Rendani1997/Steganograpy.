Steganography App
A web-based application for hiding and retrieving secret text messages within PNG images using Least Significant Bit (LSB) steganography. The app allows users to encode messages into images with minimal visual impact and later extract the hidden messages, all through a simple and intuitive interface.
Features

Hide Messages: Embed text messages into PNG images using LSB steganography.
Retrieve Messages: Extract hidden messages from encoded PNG images.
User-Friendly: Clean and straightforward interface for easy encoding and decoding.
Preserves Image Quality: Modifies only the least significant bits of pixel data to ensure minimal visual changes.

How It Works
The Steganography App uses LSB steganography to encode text by altering the least significant bits of an image’s pixel data. This method hides data in a way that is imperceptible to the human eye. To retrieve the message, the app reads these bits and reconstructs the original text.
Technologies

HTML: For the structure of the web interface.
CSS: For styling and responsive design.
JavaScript: For encoding and decoding logic.

Usage

Hide Data:
Upload a PNG image and enter your secret message.
Click "Hide Message in Image" to encode the message.
Download the modified image.


Retrieve Data:
Upload the encoded PNG image.
Click "Retrieve Hidden Message" to extract and display the hidden text.




