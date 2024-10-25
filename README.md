# Quick Note

A modern, feature-rich web-based text editor with JSON formatting, timestamp conversion, and AI-powered text improvement capabilities.

## Live Demo

Visit the live application: [Quick Note](https://tchowdary.github.io/quick-note)

No installation required! Simply open the link in your browser and start using the editor. Your content is automatically saved in your browser's local storage.

## Features

- 📝 Rich Text Editing
  - Real-time word count
  - Adjustable font size
  - Optional spell checking
  - Auto-save functionality
  - Dark/Light theme toggle

- 🔄 Format & Convert
  - JSON formatting with syntax highlighting
  - Timestamp conversion (supports both seconds and milliseconds)
  - AI-powered text improvement (requires OpenAI API key)

- 💾 Export Options
  - Export as Markdown (.md)
  - Export as JSON (.json)
  - Smart format detection

- ⌨️ Keyboard Shortcuts
  - `Esc` - Clear editor
  - `Ctrl+Shift+E` - Open export menu
  - Type `===` for a full-width separator

- 🎨 UI/UX Features
  - Auto-hiding toolbar
  - Responsive design
  - Click-to-edit formatted view
  - Toast notifications
  - Loading indicators

## Installation

1. Clone the repository:
```bash
git clone https://github.com/tchowdary/quick-note.git
```

2. Navigate to the project directory:
```bash
cd quick-note
```

3. Open `index.html` in your web browser or serve it using a local server.

## Usage

### Basic Editing
- Start typing in the editor
- Use the font size controls to adjust text size
- Toggle spell check as needed
- Dark/Light theme switch available in the top-right corner

### JSON Formatting
1. Paste your JSON into the editor
2. Click "Format JSON" button
3. View the formatted and syntax-highlighted JSON
4. Click anywhere on the formatted text to return to editing mode

### Timestamp Conversion
1. Enter a Unix timestamp (seconds or milliseconds)
2. Click "Convert Timestamp"
3. View the converted date in both UTC and local time

### AI Text Improvement
1. Click the key icon (🔑) to enter your OpenAI API key
2. Enter your text in the editor
3. Click "Improve Text"
4. View the original and improved versions

### Exporting
1. Click the "Export" button or use `Ctrl+Shift+E`
2. Choose between Markdown or JSON format
3. File will be automatically downloaded with a timestamp-based filename

## Local Storage

The application automatically saves:
- Editor content
- Theme preference
- OpenAI API key
- Font size setting

## Browser Support

Tested and supported in:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Technical Details

Built with vanilla JavaScript and uses:
- Local Storage API for data persistence
- OpenAI API for text improvement
- CSS Variables for theming
- Responsive design principles
- Modern ES6+ JavaScript features

## License

[MIT License](LICENSE)

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## Contact

Tanveer - [@0tanch](https://twitter.com/0tanch)
