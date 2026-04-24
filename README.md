# Image Color Picker

A simple, lightweight Image Color Picker built with HTML, CSS and JavaScript. Load an image, click on any pixel, and the app shows the picked color in HEX and RGB so you can copy it for design or development use.

![App screenshot](./Screenshot%202024-04-29%20140128.png)

## Features
- Pick colors from any image by clicking the pixel.
- Displays color in HEX and RGB formats.
- Copy the selected color value to the clipboard (if supported by the browser).
- Minimal, dependency-free frontend — works by opening the HTML file in a browser.

## Demo / Usage
1. Clone or download this repository.
2. Open `index.html` in your web browser (double-click the file or serve it with a simple HTTP server).
3. Use the provided file input to select an image from your computer.
4. Click anywhere on the image to pick a color. The color value will appear in the UI (HEX and RGB).
5. Click the copy button next to the color value (if available) to copy it to your clipboard.

## Installation (optional)
No build tools or package managers are required. To run locally:

- Quick (file open):
  - Open `index.html` in your browser.

- Quick (local HTTP server — recommended for some browser APIs):
  - Python 3:
    - python -m http.server 8000
    - Open http://localhost:8000 in your browser
  - Or use any static file server / Live Server from your editor.

## File structure
- index.html — main UI and markup
- styles.css (or similar) — styling for the app
- script.js (or similar) — color picking logic and clipboard handling
- Screenshot 2024-04-29 140128.png — example screenshot (used in this README)

(Adjust filenames above if your project uses different names.)

## Contributing
Contributions, bug reports, and improvements are welcome.
- If you add features (e.g., eyedropper tool enhancements, touch support, color format options), please open a PR with a short description.
- Keep changes small and focused, and include screenshots or short notes for UI changes.

## Troubleshooting
- If clicking doesn't pick a color, ensure the image fully loaded before clicking.
- If copy-to-clipboard doesn't work, check browser permissions or open the page over HTTP/HTTPS (some clipboard APIs require a secure context).

## License
Choose a license (MIT, Apache-2.0, etc.) and add a LICENSE file to the repo. Example: MIT.

## Credits
Built by BinaryVortex — Image Color Picker using plain HTML, CSS, and JavaScript.
