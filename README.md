# QR Code Generator

This is a simple Node.js command-line application that generates a QR code image from a user-provided URL and saves both the QR code as an image and the URL as a text file.

## 🔧 Features

- Prompts the user to enter a URL.
- Generates a QR code PNG image from the URL.
- Saves the entered URL in a `.txt` file for record keeping.

## 🛠️ Technologies Used

- [Node.js](https://nodejs.org/)
- [inquirer](https://www.npmjs.com/package/inquirer) - for interactive CLI prompts
- [qr-image](https://www.npmjs.com/package/qr-image) - for generating QR codes
- [fs (File System)](https://nodejs.org/api/fs.html) - built-in Node.js module for file operations

## 📦 Installation

1. Clone the repository:

```bash
git clone https://github.com/aftabmumtaz123/QR_Generator.git
cd QR_Generator
Install dependencies:

bash
Copy
Edit
npm install inquirer qr-image
🚀 Usage
Run the app using Node.js:

bash
Copy
Edit
node index.js
You’ll be prompted to enter a URL.

After entering the URL:

A QR code image (qr_img.png) will be generated in the current directory.

The URL will also be saved to a file named QrCodeFile.txt.
```
## 📂 Output Files
qr_img.png: The generated QR code image.

QrCodeFile.txt: Contains the plain text of the URL.

## 📝 License
This project is open source and available under the MIT License.
