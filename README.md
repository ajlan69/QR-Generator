# QuickToolBox QR Code Generator

Standalone production-style QR generator page.

## Run
Open `qr-code-generator.html` with VS Code Live Server.

## Features
- Real standards-compliant QR generation using qrcode-generator 2.0.4
- URL and text input
- UTF-8 byte encoding
- Error correction L/M/Q/H
- QR/background color customization
- Quiet-zone control
- 256/512/1024/2048 PNG sizes
- PNG download
- SVG download
- Responsive UI
- No backend
- No user payload is sent to a QR generation API

## Dependency
The page currently loads the pinned MIT-licensed `qrcode-generator@2.0.4` browser build from jsDelivr. For a zero-third-party-runtime deployment, download/vendor the same `dist/qrcode.js` file into `vendor/` and replace the script URL with a local path.

Official project:
https://github.com/kazuhikoarase/qrcode-generator

## Production
Replace `YOUR-DOMAIN.example` in canonical/Open Graph URLs with the real domain.
