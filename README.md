# LSB-3DES
Steganography with Cryptography
PROJECT OVERVIEW: 
This Python project hides (encodes) a secret encrypted message inside an image using the Least Significant Bit (LSB) technique. The message is first encrypted using Triple DES (3DES) for security, and then the encrypted data is hidden in the image.
Later, the user can decode and decrypt the message from the image.
Required libraries:
Pillow (for image processing)
pycryptodome (for encryption)
hashlib (for MD5 key hashing)
---Install all the required packages---
Steps to Run the Project (Encoding & Decoding)
1. Place a default image in your project folder for encoding (e.g., image.png).
2. Run the Python file using
3. Select your option when prompted
4. Enter the symmetric key (used for both encryption and decryption).
5. For encoding:
Enter the image name with extension (e.g., image.png)
Enter the new image name with extension for the encoded output (e.g., encoded.png)
6. For decoding:
Enter the same choice (2)
Provide the same symmetric key
Enter the encoded image name used in step 5 (e.g., encoded.png)
7. View the decoded message displayed on the screen.


Have a image in default in your project folder for basic encoding proces
1. Run your python file
2. Enter your choice
3. Give the symmetric key
4. give the image name with extension for encoding 
5. Create a new image with extension for encoded output
6. for decoding enter the same above steps choice, symmetric key and encoded output image with extension
7. finally u can get the decoded message
