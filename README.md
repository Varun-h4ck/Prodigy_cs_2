Image Encryptor 🖼️🔐

A simple Python application for encrypting and decrypting images using a basic additive cipher. This project uses the Python Imaging Library (PIL) and NumPy for image manipulation.

Features✨

Encrypt images by shifting pixel values using a specified key.
Decrypt previously encrypted images with the same key.
Easy-to-use command-line interface.

📦Requirements 
Python 3.x
Pillow (PIL Fork)
NumPy

⚙️ Usage :

🔐 Encrypting an Image:

Run the script.
Enter an encryption key (integer).
Provide the path to the image you want to encrypt.
Specify where to save the encrypted image.

🌐 Decrypting an Image:

After encryption, decrypt the image.
Enter the path of the encrypted image.
Specify where to save the decrypted image.

🔍 How It Works

The image is loaded and converted into a NumPy array.
Pixel values are shifted by the encryption key (addition for encryption, subtraction for decryption).
The modified pixel values are saved back as a new image.

🤝 Contributing 
Contributions are welcome! If you have suggestions or improvements, please create a pull request or open an issue.








