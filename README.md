# QRDecode – QR Code to Link Converter

A professional, responsive web app that decodes QR codes from images or a live camera feed. Extract URLs, plain text, Wi-Fi credentials, vCards, and more. 100% client-side and privacy-friendly.

## Features

- Upload or drag & drop QR code images (PNG, JPG, WEBP, GIF, BMP)
- Scan QR codes directly with your camera
- Paste images from the clipboard (Ctrl+V / Cmd+V)
- Multi-pass decoding: grayscale, high-contrast, inverted, and upscaling
- Auto-detect content type: URL, Wi-Fi, vCard, email, phone, SMS, geo location, and plain text
- Copy decoded text or open the link directly
- Dark/light theme toggle with `localStorage` persistence
- Fully responsive and mobile-friendly
- No server, no data leaves your device

## How to Use

1. Open `index.html` in a modern browser.
2. Upload a QR image, drag & drop it, paste it, or click **Use camera**.
3. View the decoded content and its type badge.
4. Copy the text or open the link (if applicable).
5. Use the theme toggle to switch between light and dark mode.

> **Note:** Camera scanning requires a secure context (`https://` or `http://localhost`) and permission from the browser. If the camera does not start, serve the project through a local server (for example `npx serve` or `python -m http.server`) instead of opening the file directly.

## Technologies

- HTML5
- [Tailwind CSS](https://tailwindcss.com/) (via CDN)
- JavaScript (ES6)
- [jsQR](https://github.com/cozmo/jsQR) for QR decoding
- [Font Awesome](https://fontawesome.com/) icons
- [Google Fonts](https://fonts.google.com/) (Inter)

## Browser Support

Works in all modern browsers: Chrome, Firefox, Safari, and Edge.

## Privacy

All processing happens locally in your browser. No images or data are uploaded to any server.

## License

Free to use and modify.
