# 📱 QR Code Scan & Generate Web App

A simple and interactive **web application** that allows users to **generate** QR codes from any text or URL and **scan** QR codes using their device’s webcam in real time.  
This project was built to practice **API calls, JavaScript, Node.js basics, and modern web development techniques**.

---

## ✨ Features

- ⚡ **Generate QR Codes instantly** using the [QRServer API](https://api.qrserver.com).  
- 💾 **Download QR codes** as image files for later use.  
- 📷 **Scan QR Codes live** from the webcam with real-time decoding.  
- 📝 **Display scan results** on a dedicated results page.  
- 🎨 **Responsive and user-friendly interface** with smooth animations.  

---

## 🛠️ Technologies Used

- **Frontend:** HTML5, CSS3, JavaScript (ES6)  
- **Libraries:** [html5-qrcode](https://github.com/mebjas/html5-qrcode)  
- **API:** [QRServer.com API](https://api.qrserver.com)  
- **Node.js** (for scanner dependencies & local server setup)  

---

## 📂 Project Structure
```
QR_scan_generate/
│
├── .git/                     # Git version control folder
│
├── Generate/                 # QR code generator module
│   ├── base.html              # QR generation HTML page
│   ├── generate.js            # QR code generation JavaScript logic
│   └── style.css              # CSS styles for generator module
│
├── Scan/                     # QR code scanner module
│   ├── index.html             # Scanner main HTML page
│   ├── result.html            # Page to display scan results
│   ├── package.json           # Node dependencies manifest
│   ├── package-lock.json      # Locked dependencies versions
│   ├── style.css              # CSS styles for scanner
│   └── node_modules/          # Installed node modules
│
├── index.html                 # Landing page (navigate to Generate/Scan)
├── style.css                  # Common CSS styles for landing page
├── README.md                  # Project documentation
├── generate.js                # Optional: generator JS outside module
├── result.html                # Optional: scan results page (if outside Scan/)
├── image.jpg                  # Sample/placeholder image
└── Other config/resources
```

---

## 🚀 Installation & Usage

### 1. Clone the repository
```bash
git clone https://github.com/yourusername/QR_scan_generate.git
cd QR_scan_generate
```

### 2. Run the project

- **For QR Code Generator**  
Open `/Generate/base.html` or `index.html` directly in your browser.

- **For QR Code Scanner**  
⚠️ Requires a local server for webcam access.  

Run one of the following:

```bash
# Using Python
python -m http.server

# Using Node.js
npx http-server
```

Then visit 👉 `http://localhost:8000/Scan/index.html`  

---

## 🤝 Contribution
Contributions are welcome!  
1. Fork the repo  
2. Create a new branch (`feature/your-feature-name`)  
3. Commit changes and push  
4. Open a pull request 🚀  

---

## 📜 License
This project is licensed under the **MIT License** – free to use and modify.  

---

### 🌟 Star this repo if you find it useful!
