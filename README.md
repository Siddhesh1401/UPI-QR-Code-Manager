# 💳 UPI QR Manager

A modern, futuristic web application for managing multiple UPI IDs and generating QR codes for payments. Built with vanilla JavaScript, no dependencies required except for QR code generation.

## ✨ Features

- 🎨 **Stunning UI** - Dark mode with glass-morphism effects and neon accents
- 💾 **Local Storage** - All your UPI profiles are saved securely on your device
- 📱 **Mobile Optimized** - Fully responsive design, works perfectly on phones
- ⚡ **Fast & Lightweight** - No frameworks, pure HTML/CSS/JS
- 🔒 **Privacy First** - Everything runs client-side, no data sent to servers
- 📤 **Share QR Codes** - Native share functionality for mobile devices
- ⬇️ **Download QR Codes** - Save generated QR codes as PNG images

## 🚀 Live Demo

**Access the app here:** [https://siddhesh1401.github.io/UPI-QR-Code-Manager/](https://siddhesh1401.github.io/UPI-QR-Code-Manager/)

## 📱 How to Use

### 1. Add UPI Profiles
- Click the **"+ Add UPI"** button in the header
- Enter:
  - **Card Name**: A label for this profile (e.g., "Personal", "Business", "Shop")
  - **UPI ID**: Your UPI address (e.g., username@bankname)
  - **Payee Name**: Name that will appear in the payment request
- Click **"Save"**

### 2. Generate QR Codes
- Click on any saved UPI card
- Enter the payment amount
- Add an optional note
- Click **"Generate QR Code"**
- Share or download the QR code

### 3. Manage Profiles
- **Edit** ✏️: Click the edit icon on any card to update details
- **Delete** 🗑️: Click the delete icon to remove a profile

## 🎯 Installation on Mobile

### For Android (Chrome/Firefox)
1. Open the app URL in your browser
2. Tap the menu (⋮) → **"Add to Home screen"** or **"Install app"**
3. The app will appear as an icon on your home screen

### For iOS (Safari)
1. Open the app URL in Safari
2. Tap the **Share button** (square with arrow)
3. Scroll and tap **"Add to Home Screen"**
4. Tap **"Add"**

## 💻 Local Development

### Run Locally
```bash
# Clone the repository
git clone https://github.com/Siddhesh1401/UPI-QR-Code-Manager.git
cd UPI-QR-Code-Manager

# Start a local server (Python 3)
python -m http.server 8000

# Or use Node.js
npx serve

# Open in browser
# http://localhost:8000
```

### File Structure
```
├── index.html          # Main application file (all-in-one)
└── README.md          # This file
```

## 🛠️ Technical Details

- **No Build Process** - Single HTML file with embedded CSS and JavaScript
- **QR Code Library** - Uses qrcodejs (loaded via CDN)
- **Storage** - Browser localStorage API
- **Fonts** - Google Fonts (Inter)
- **Compatibility** - Works on all modern browsers

## 🔧 Technologies Used

- HTML5
- CSS3 (Animations, Gradients, Backdrop Filters)
- Vanilla JavaScript (ES6+)
- QRCode.js Library
- LocalStorage API
- Web Share API (for mobile sharing)

## 🎨 Design Features

- Dark theme with gradient backgrounds
- Animated grid pattern overlay
- Glass-morphism effects (backdrop blur)
- Smooth transitions and hover effects
- Neon glow on interactive elements
- Responsive grid layout
- Custom scrollbar styling

## 🔐 Privacy & Security

- ✅ All data stored locally on your device
- ✅ No data sent to external servers
- ✅ No tracking or analytics
- ✅ Works completely offline after first load
- ✅ UPI strings follow standard UPI deep-link format

## 📝 UPI String Format

Generated QR codes use the standard UPI URL format:
```
upi://pay?pa=<UPI_ID>&pn=<NAME>&am=<AMOUNT>&cu=INR&tn=<NOTE>
```

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Report bugs
- Suggest features
- Submit pull requests

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👤 Author

**Siddhesh**
- GitHub: [@Siddhesh1401](https://github.com/Siddhesh1401)

## 🌟 Show Your Support

Give a ⭐️ if you like this project!

## 📞 Support

For issues or questions, please open an issue on GitHub.

---

**Made with 💜 by Siddhesh**
