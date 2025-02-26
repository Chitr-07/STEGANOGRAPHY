# SECURE DATA HIDING IN IMAGES USING STEGANOGRAPHY

This project provides a simple implementation of **image-based steganography**, where secret messages are hidden within an image and later retrieved using a decryption script. The encryption and decryption processes involve modifying the pixel values of an image to store message bytes.

## Features

- Hide a secret message inside an image using pixel manipulation.
- Secure the message with a password.
- Extract the hidden message only with the correct password.
- Simple and lightweight implementation using Python and OpenCV.

## Usage

### 1. Encrypting a Message

To hide a secret message in an image:

#### Steps:

1. change the image file path (`tiger.jpeg`).
2. Enter the secret message you want to hide.
3. Provide a password for security.
4. The encrypted image is saved as `encryptedImage.png`.


### 2. Decrypting a Message

To retrieve the hidden message from the encrypted image:

#### Steps:

1. The script reads `encryptedImage.png`.
2. You must enter the correct password.
3. If the password matches, the hidden message is displayed.
4. If the password is incorrect, access is denied.

## File Description

- **encryptedImage.png** - Image containing the hidden message.
- **tiger.jpeg** - Original image used for encryption.
- **main.py** - code for the encryption and decryption.

## License

This project is open-source and available under the MIT License.





