# Steganography
Requirement: Python 3 pip install CV2
This project demonstrates a simple implementation of image steganography using Python and OpenCV. The application allows users to hide (encrypt) a secret message inside an image and later retrieve (decrypt) the message using a simple UI built with Tkinter.
Data Concealment in Images – Hides text or binary data within image files without significant visual distortion.
Least Significant Bit (LSB) Technique – Uses LSB modification to embed data in pixel values.
Encryption Support – Encrypts the message before hiding it for added security.
Lossless Data Extraction – Recovers the exact hidden message from the image.
Support for Various Image Formats – Works with PNG, BMP, and other lossless formats.
Customizable Payload Capacity – Determines how much data can be embedded based on image size.
Password Protection – Restricts access to extraction with a user-defined key.
Graphical User Interface (GUI) – Can be integrated with Tkinter or PyQt for user-friendly interaction.
Command-line Interface (CLI) Support – Allows encoding and decoding through terminal commands.
Efficient and Fast Processing – Optimized for quick encoding and decoding operations.
