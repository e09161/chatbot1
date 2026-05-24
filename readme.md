# DeepSeek Chat Interface

A modern, feature-rich chat interface for DeepSeek AI with file attachments, Markdown rendering, and code validation.

## Features

- 💬 **Multiple Chat Sessions** - Create and manage multiple conversations
- 📎 **File Attachments** - Drag & drop or click to attach files (supports .py, .xml, .txt, .html, .js, .css, .json, .md, .csv)
- 🎨 **Markdown Rendering** - Proper display of formatted text, tables, code blocks, and more
- 🔍 **Code Validation** - Built-in validator for Python and generic code syntax
- 💾 **Export/Import** - Backup and restore your chat history
- 📱 **Responsive Design** - Works on desktop and mobile devices
- 🔒 **Local Storage** - All data stored locally in your browser
- 🎯 **Multiple Models** - Support for different DeepSeek models

## Setup

1. Get an API key from [DeepSeek Platform](https://platform.deepseek.com/)
2. Open `index.html` in your browser
3. Enter your API key and click "Save"
4. Start chatting!

## Deploy to GitHub Pages

1. Fork or clone this repository
2. Go to repository Settings > Pages
3. Select your main branch as the source
4. Your chat interface will be live at `https://[username].github.io/[repo-name]/`

## Usage

### Chat Management
- Click "+ New Chat" to start a fresh conversation
- Click on chat titles in the sidebar to switch between conversations
- Click "×" to delete unwanted chats

### File Attachments
- Drag files directly onto the input area
- Click the 📎 button to browse files
- Supported formats: .py, .xml, .txt, .html, .js, .css, .json, .md, .csv
- Maximum file size: 1MB per file

### Code Features
- Code blocks are automatically detected and formatted
- Click "Copy" to copy code to clipboard
- Click "Download" to save code as a file
- Click 🔍 to validate code syntax
- Use "Validate All" button to check all code blocks

### Data Management
- **Export** - Save all chats as a JSON file
- **Import** - Restore chats from a JSON file
- All data is stored locally in your browser's localStorage

## Technical Details

- Pure HTML/CSS/JavaScript - no build process required
- Uses [marked.js](https://marked.js.org/) for Markdown rendering
- All API calls go directly to DeepSeek's official endpoint
- No server required - works completely client-side

## Privacy

- Your API key is stored only in your browser's localStorage
- Chat data never leaves your device (except when sending to DeepSeek API)
- No analytics, tracking, or external services (except marked.js CDN and DeepSeek API)

## License

MIT - Feel free to modify and use as you wish!
