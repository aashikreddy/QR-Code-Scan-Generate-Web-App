# QR Code Scan & Generate Web App

## Project Overview
This project is a web application that allows users to generate QR codes from any text or URL and scan QR codes using their device's webcam. It was developed to learn API calls, JavaScript, and modern web development techniques.

## Features
- Generate QR codes instantly using an external API.
- Download generated QR codes as image files.
- Scan QR codes live from the webcam with real-time results.
- Display scan results on a dedicated results page.
- Responsive and user-friendly interface with smooth animations.

## Technologies Used
- HTML5 & CSS3
- JavaScript (ES6)
- [html5-qrcode](https://github.com/mebjas/html5-qrcode) library for scanning
- [qrserver.com API](https://api.qrserver.com) for QR code generation

## Installation & Usage
1. Clone the repository:
git clone https://github.com/yourusername/qr-scan-generate.git
cd qr-scan-generate
2. Open the `index.html` file in a modern web browser.
3. Use the "Generator" button to create QR codes.
4. Use the "Scanner" button to scan QR codes using your webcam.

## How to Run the Web Application
For best compatibility, especially when accessing the webcam, consider running a local web server:

| Command                 | Description                           |
|-------------------------|-------------------------------------|
| `python -m http.server` | Run a simple HTTP server (Python 3) |
| `npx http-server`        | Run a simple HTTP server (Node.js)  |

After starting the server, open your browser at `http://localhost:8000` (or the specified port).

## Contribution
Feel free to fork, modify, and submit pull requests for improvements.

## License
This project is licensed under the MIT License.
