# Advanced QR Code Tools 📱

A comprehensive web application for scanning, generating, and managing QR codes with support for multiple formats including WiFi, URLs, text, email, and phone numbers.

## 🌐 Live Demo

**Website:** [https://webgamerstudio.github.io/Advanced-QR-Code-Tools/generator.html](https://webgamerstudio.github.io/Advanced-QR-Code-Tools/generator.html)

## ✨ Features

### 📷 Camera Scanner
- Real-time QR code scanning using device camera
- Auto-detection of QR code types
- Support for front and back camera
- Instant results with formatted display

### 🔗 QR Code Generator
- Generate QR codes for multiple formats:
  - 🌐 Website URLs
  - 📝 Plain text
  - 📶 WiFi credentials
  - 📧 Email addresses
  - 📞 Phone numbers
- Customizable options:
  - Size (128px to 1024px)
  - Colors (foreground and background)
  - Error correction levels
- Download as PNG
- Share functionality

### 📂 Image Upload Scanner
- Upload QR code images from device
- Drag and drop support
- Support for multiple image formats (JPG, PNG, GIF, BMP, WebP)
- File size limit: 10MB

### 📊 Scan History
- Automatic saving of scanned QR codes
- Statistics dashboard
- Recent scans list with timestamps
- Clear history option

## 🎯 Supported QR Code Types

| Type | Icon | Description |
|------|------|-------------|
| WiFi | 📶 | Network credentials with SSID, password, and security type |
| URL | 🌐 | Website links with domain parsing |
| Email | 📧 | Email addresses with subject and body support |
| Phone | 📞 | Phone numbers with direct calling |
| Text | 📝 | Plain text content |

## 🚀 Getting Started

### Prerequisites
- Modern web browser with camera support
- JavaScript enabled
- Internet connection (for QR generation API)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/webgamerstudio/Advanced-QR-Code-Tools.git
   ```

2. Navigate to project directory:
   ```bash
   cd Advanced-QR-Code-Tools
   ```

3. Open `index.html` in your web browser or serve using a local server.

### File Structure
```
Advanced-QR-Code-Tools/
├── index.html          # Landing page with WebGamer STUDIO branding
├── Home.html           # Main scanner interface
├── generator.html      # QR code generator
├── upload.html         # Image upload scanner
└── README.md          # Project documentation
```

## 🛠️ Technology Stack

- **Frontend:** HTML5, CSS3, JavaScript (ES6+)
- **QR Scanning:** Html5-QRCode library
- **QR Generation:** QR Server API
- **Styling:** Custom CSS with gradient designs
- **Storage:** LocalStorage for history management

## 📱 Mobile Responsive

The application is fully responsive and optimized for:
- Desktop browsers
- Tablet devices
- Mobile phones (iOS/Android)

## 🎨 Design Features

- Modern gradient-based design
- Smooth animations and transitions
- Intuitive user interface
- Accessibility-friendly
- Print-optimized styles

## 🔒 Privacy & Security

- All QR code scanning happens locally in your browser
- No data is sent to external servers during scanning
- History is stored locally on your device
- QR generation uses external API but doesn't store data

## 📋 Browser Compatibility

- Chrome 60+
- Firefox 55+
- Safari 11+
- Edge 79+
- Mobile browsers with camera support

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

### Development Setup
1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test across different browsers
5. Submit a pull request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 📞 Contact

**Developer:** WebGamer STUDIO  
**Email:** [webgamerconnect@gmail.com](mailto:webgamerconnect@gmail.com)  
**Website:** [https://webgamerstudio.github.io/Advanced-QR-Code-Tools/](https://webgamerstudio.github.io/Advanced-QR-Code-Tools/)

## 🙏 Acknowledgments

- [Html5-QRCode](https://github.com/mebjas/html5-qrcode) for QR code scanning functionality
- [QR Server API](https://goqr.me/api/) for QR code generation
- Inspired by modern web design practices

## 📈 Roadmap

- [ ] Add bulk QR code generation
- [ ] Implement QR code batch scanning
- [ ] Add more customization options
- [ ] Support for additional QR code formats
- [ ] Offline functionality with service workers
- [ ] Export history as CSV/JSON

## 🐛 Bug Reports & Feature Requests

If you encounter any issues or have feature suggestions, please:
1. Check existing issues first
2. Create a detailed bug report or feature request
3. Contact us at [webgamerconnect@gmail.com](mailto:webgamerconnect@gmail.com)

---

**Made with ❤️ by WebGamer STUDIO**  
*Creative Web Experience from Bangladesh*