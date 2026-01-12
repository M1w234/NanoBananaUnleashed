[README (2).md](https://github.com/user-attachments/files/24564354/README.2.md)
# 🍌 Nana Banana Unleashed - Gemini Image Tools

A powerful, browser-based image editing and generation tool powered by Google's Gemini AI. Edit existing images with natural language prompts or generate stunning new images from scratch - all running entirely in your browser.

![Version](https://img.shields.io/badge/version-1.0.0-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![React](https://img.shields.io/badge/React-18-61dafb)
![Gemini](https://img.shields.io/badge/Gemini-AI-orange)

**[🚀 Try it Now](https://m1w234.github.io/NanoBananaUnleashed/)**

---

## Features

### Dual Mode Operation
- **Edit Mode**: Transform existing images using AI-powered edits with natural language prompts
- **Generate Mode**: Create original images from text descriptions

### Core Capabilities
- **Drag & Drop Interface**: Intuitive image upload with visual feedback
- **Multiple AI Models**: Choose from various Gemini models (Flash 2.0, Exp-1206, Pro-002, Flash-8B)
- **History Tracking**: Automatically saves all generations and edits with timestamps
- **Collection System**: Curate your favorite creations in a personal gallery
- **Full-Size Preview**: Click any image for an immersive modal view
- **Batch Download**: Export individual images or entire collections
- **Persistent Storage**: IndexedDB integration ensures your work survives browser sessions

### User Experience
- **No Backend Required**: Runs entirely in the browser - no server setup needed
- **Secure API Key Storage**: Your credentials stay local in your browser
- **Responsive Design**: Beautiful interface built with Tailwind CSS
- **Instant Feedback**: Real-time loading states and error handling
- **Smart History**: Chronologically organized with source tracking

---

## Technology Stack

- **Frontend Framework**: React 18
- **Styling**: Tailwind CSS
- **AI Integration**: Google Gemini API
- **Storage**: IndexedDB for image persistence, LocalStorage for settings
- **Icons**: Lucide React
- **Build**: Single-file HTML application (no build step required!)

---

## Prerequisites

Before you begin, you'll need:
- A modern web browser (Chrome, Firefox, Safari, Edge)
- A Google Gemini API key ([Get one here](https://aistudio.google.com/app/apikey))

---

## Getting Started

### Option 1: Use the Live Version

**Visit the live app**: [https://m1w234.github.io/NanoBananaUnleashed/](https://m1w234.github.io/NanoBananaUnleashed/)

### Option 2: Run Locally

1. **Clone or Download** this repository
   ```bash
   git clone https://github.com/m1w234/NanoBananaUnleashed.git
   ```

2. **Open the HTML file** in your browser
   - Simply double-click `index.html`
   - Or serve it with any local server

3. **Add Your API Key**
   - Click the ⚙️ settings icon in the top-right
   - Paste your Gemini API key
   - Select your preferred model
   - Click "Save Settings"

4. **Start Creating!**
   - Switch between Edit and Generate modes
   - Upload images or describe what you want to create
   - Watch the magic happen

---

## Usage Guide

### Editing Images

1. Click the **Edit** tab
2. Drag and drop an image or click to upload
3. Enter a natural language prompt describing your desired changes:
   - "Make the sky purple and add stars"
   - "Remove the background"
   - "Change this to a watercolor painting style"
4. Click "Edit with AI" and wait for the magic!

### Generating Images

1. Click the **Generate** tab
2. Describe the image you want to create:
   - "A serene mountain landscape at sunset"
   - "A futuristic city with flying cars"
   - "A cute robot playing with a puppy"
3. Click "Generate Image" and watch your vision come to life!

### Managing Your Work

- **History**: View all your past generations with source images and prompts
- **Collection**: Save favorite images by clicking the star icon
- **Download**: Click download buttons to save individual images
- **Preview**: Click any image for a full-screen view

---

## Available Models

| Model | Best For | Speed | Quality |
|-------|----------|-------|---------|
| Gemini Flash 2.0 | Fast iterations | ⚡⚡⚡ | ⭐⭐⭐ |
| Gemini Exp-1206 | Experimental features | ⚡⚡ | ⭐⭐⭐⭐ |
| Gemini Pro-002 | Highest quality | ⚡ | ⭐⭐⭐⭐⭐ |
| Gemini Flash-8B | Ultra-fast testing | ⚡⚡⚡⚡ | ⭐⭐ |

---

## Privacy & Security

- **API keys are stored locally** in your browser's LocalStorage
- **No data is sent to external servers** except Google's Gemini API
- **Images are stored in IndexedDB** on your device only
- **No tracking or analytics** - your privacy is respected

---

## Customization

The application is built as a single HTML file, making it easy to customize:

- **Styling**: Modify Tailwind classes or add custom CSS in the `<style>` section
- **Models**: Update the `availableModels` array to add/remove AI models
- **Features**: The React component structure makes adding new features straightforward

---

## Troubleshooting

### API Key Issues
- Ensure your API key is valid and active
- Check that you have API credits remaining
- Verify the selected model is available in your region

### Images Not Saving
- Check browser console for errors
- Ensure IndexedDB is enabled in your browser
- Try clearing browser cache and reloading

### Generation Failures
- Some prompts may be filtered by safety settings
- Try rephrasing your prompt
- Switch to a different model

---

## Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## Roadmap

- [ ] Add batch image processing
- [ ] Implement style presets
- [ ] Add prompt history and suggestions
- [ ] Support for video generation (when available)
- [ ] Export/import collections
- [ ] Add undo/redo functionality
- [ ] Implement image-to-image variations

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Acknowledgments

- **Google Gemini** for providing the powerful AI capabilities
- **React Team** for the amazing framework
- **Tailwind CSS** for the beautiful styling system
- **Lucide** for the clean, modern icons

---

## Contact

**Michael Wong** - [Team Wong Hawaii](https://teamwonghawaii.com)

**Project Link**: [https://m1w234.github.io/NanoBananaUnleashed/](https://m1w234.github.io/NanoBananaUnleashed/)

---

<div align="center">
  <strong>Powered by Google Gemini AI</strong>
  <br>
  Made with ❤️ for creators and dreamers
</div>
