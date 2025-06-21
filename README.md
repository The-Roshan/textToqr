# 📱 QR Code Generator

## Overview
The QR Code Generator is a sleek, web-based application created by Roshan Kumar Prajapati. Built with HTML, CSS, and JavaScript, it allows users to generate QR codes from text input (up to 300 characters) in real-time. The application features a modern interface with a particle animation background on a canvas, a glassmorphism-styled container, and smooth hover effects. It uses the QRCode.js library for QR code generation and is optimized for both desktop and mobile devices, offering a visually appealing and functional experience.

## Features
- **QR Code Generation** 📷:
  - Generates QR codes from user input in a textarea (`text`) with a 300-character limit.
  - Displays the QR code in a dedicated container (`qrCode`) with customizable colors.
- **Input Validation** ✅:
  - Alerts users if the input is empty or exceeds 300 characters for optimal scan quality.
- **Animated Background** ✨:
  - Canvas-based particle animation with random sizes, colors, and movement, creating a dynamic backdrop.
- **Modern Design** 🎨:
  - Glassmorphism container with blur effect, hover animations, and a gradient button.
  - Dark blue theme (`#0e2a47`) with light text and input fields for a clean aesthetic.
- **Responsive Design** 📱:
  - Optimized for various screen sizes with flexible layouts and canvas resizing.
- **External Dependency** 📚:
  - QRCode.js (version 1.0.0 via CDN) for generating QR codes.

## Tech Stack
- **HTML5**: Structure of the application, including textarea, button, and canvas.
- **CSS3**: Styling for the container, button, textarea, and particle animations (inline styles in `index.html`).
- **JavaScript**: Logic for QR code generation, particle animation, and input validation (inline script in `index.html`).
- **Canvas API**: Used for rendering the particle background.
- **QRCode.js**: Library for generating QR codes.

## Project Structure
```
qr-code-generator/
├── index.html         # Main HTML file
├── LICENSE.md        # MIT License
└── README.md         # This file
```

## Prerequisites
- A modern web browser (e.g., Chrome, Firefox, Edge) with Canvas and JavaScript support.
- A code editor (e.g., VS Code) for customization.
- Internet connection for loading QRCode.js from CDN (or download locally for offline use).

## Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/The-Roshan/qr-code-generator.git
cd qr-code-generator
```

### 2. Open the Website
- Open `index.html` in a web browser:
  ```bash
  open index.html  # macOS
  start index.html  # Windows
  ```
- Alternatively, use a local development server (e.g., VS Code Live Server) for better performance.

### 3. Customize (Optional)
- Edit inline CSS in `index.html` to modify colors, particle animations, or glassmorphism effects.
- Update inline JavaScript in `index.html` to enhance particle behavior, adjust QR code size, or add features like QR code downloading.
- Modify `index.html` to add new UI elements (e.g., a reset button or URL validation).

## Usage
1. **Enter Text** ✍️: Type up to 300 characters in the textarea (e.g., a URL, message, or contact info).
2. **Generate QR Code** 📷: Click the "Generate QR Code" button to create a scannable QR code.
3. **View QR Code** 🖼️: The QR code appears below the button, ready for scanning.
4. **Animated Background** ✨: Enjoy the particle animation in the background.
5. **Responsive** 📱: Access the generator on mobile or desktop for a consistent experience.

## Deployment
- **Static Hosting**:
  1. Upload `index.html` to a hosting service (e.g., GitHub Pages, Netlify, Vercel).
  2. Configure the service to serve `index.html` as the entry point.
- **GitHub Pages Example**:
  1. Push the repository to GitHub.
  2. Enable GitHub Pages in the repository settings, selecting the `main` branch.
  3. Access the site at `https://the-roshan.github.io/qr-code-generator`.
- **Netlify Example**:
  1. Drag the project folder into Netlify’s dashboard.
  2. Deploy and use the provided URL.
- **Local Server**:
  ```bash
  python -m http.server 8000
  ```
  Visit `http://localhost:8000`.

## Notes
- **JavaScript Logic**: The inline script in `index.html` handles:
  - Particle animation with dynamic sizing, coloring, and movement.
  - QR code generation using QRCode.js with input validation.
  - Canvas resizing on window resize events.
- **Styling**: Inline CSS in `index.html` manages all styles, including glassmorphism, hover effects, and particle animations. Consider moving styles to a separate `style.css` file for maintainability.
- **QRCode.js Dependency**: Uses QRCode.js via CDN (`https://cdnjs.cloudflare.com/ajax/libs/qrcodejs/1.0.0/qrcode.min.js`). Download locally for offline use if needed.
- **Enhancements**: Consider adding:
  - A download button to save the QR code as an image.
  - Input presets (e.g., URL, email, phone) for quick generation.
  - Additional particle effects or background customization options.
  - Error handling for invalid QR code content.
- **SEO**: Add meta tags in `<head>` (e.g., `description`, `keywords`) for better visibility, e.g., "QR code generator by Roshan Kumar Prajapati".
- **License**: Include the MIT License in `LICENSE.md` to clarify usage terms (as provided previously).
- **Performance**: Optimize particle count for low-end devices to prevent lag.

## License
This project is licensed under the MIT License. See `LICENSE.md` for details.

## Contributing
1. Fork the repository.
2. Create a feature branch: `git checkout -b feature/your-feature`.
3. Commit changes: `git commit -m "Add your feature"`.
4. Push to the branch: `git push origin feature/your-feature`.
5. Open a pull request.

## Acknowledgments
- Built with HTML, CSS, and JavaScript for a modern and functional QR code tool.
- Inspired by sleek UI designs with glassmorphism and particle animations.
- Created by Roshan Kumar Prajapati.

## Contact
For questions or feedback, contact Roshan Kumar Prajapati:
- 📧 Email: roshanjsr5555@gmail.com
- 📞 Phone: +91 7061126213
- 🌐 GitHub: [The-Roshan](https://github.com/The-Roshan)
