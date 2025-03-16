# 🔐 Steganography Software

This project implements **steganography** in images, allowing users to **hide secret messages** inside an image and later extract them using a password.

## 📌 Features
- **Encode text** into an image using **Least Significant Bit (LSB) modification**.
- **Support for password protection** to secure the hidden message.
- **Decode hidden messages** from an image, requiring the correct password for decryption.
- **Supports encoding from text input or file input**.

## 🛠️ Technologies Used
- Python
- Jupyter Notebook
- **Pillow (PIL)** for image processing

### Encoding a Message
1. Enter the image file name (e.g., `image.png`).
2. Choose between entering a **text message** or reading from a **text file**.
3. Set a **password** for the message.
4. Enter a name for the output image (e.g., `encoded_image.png`).

### Decoding a Message
1. Enter the **encoded image** file name.
2. Enter the **password** used during encoding.
3. If the password is correct, the hidden message is revealed.

## Example
```
:: Welcome to Steganography ::
1. Encode
2. Decode
Choose: 1
Enter image name: sample.png
Enter data to be encoded: Hello, World!
Set a password: 1234
Enter the name of new image: hidden.png
Data encoded successfully in hidden.png
```



---
Developed by **Supriya Mishra**
