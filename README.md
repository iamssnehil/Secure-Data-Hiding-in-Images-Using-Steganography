# Secure-Data-Hiding-in-Images-Using-Steganography

This project is a **GUI-based Image Steganography tool** built using **Python** and **Tkinter**, allowing users to hide and retrieve secret messages within images using a passcode.

## 🚀 Features

- **Encrypt text messages inside images** 🔒
- **Decrypt hidden messages from images** using the correct passcode 🔑
- **User-friendly interface** with side-by-side encryption & decryption
- **Passcode-based security** with hashing for verification 🔐

## 📷 How It Works

1. **Encryption**

   - Select an image.
   - Enter a secret message and passcode.
   - The tool embeds the message into the image and saves it.

2. **Decryption**

   - Select the encrypted image.
   - Enter the correct passcode.
   - The tool retrieves and displays the hidden message.

## 🛠 Technologies Used

- **Python** 🐍
- **Tkinter** (for GUI) 🎨
- **OpenCV (cv2)** (for image processing) 🖼
- **Hashlib** (for passcode security) 🔑

## 📥 Installation & Usage

### Prerequisites

Ensure you have Python installed (preferably Python 3.8 or newer).

### Install Dependencies

```sh
pip install opencv-python pillow
```
