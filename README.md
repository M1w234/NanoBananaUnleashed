# Nana Banana Unleashed

**Browser-based AI image suite powered by Google Gemini & OpenAI Vision**

Use your own API keys for AI image analysis, editing, and generation — no subscriptions, no backend, no data leaving your browser.

![Version](https://img.shields.io/badge/version-1.0.0-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![React](https://img.shields.io/badge/React-18-61dafb)
![Gemini](https://img.shields.io/badge/Gemini-AI-orange)

**[Try it Now](https://m1w234.github.io/NanoBananaUnleashed/)**

---

## Why Use This?

- **Your Keys, Your Control** — Direct API access, no middleman service taking a cut
- **Pay Only What You Use** — API costs typically $0.002–0.02 per generation vs $20+/mo subscriptions
- **Fully Local & Private** — All data stored in IndexedDB on your device. Nothing uploaded to external servers
- **No Setup Required** — Single HTML file, no build step, no backend. Just open and go
- **Unlimited Parallel Processing** — Run as many simultaneous generations as your API quota allows

---

## Features

### Five Modes

| Mode | What It Does |
|------|-------------|
| **Analyze** | Upload images and get AI-powered descriptions and analysis |
| **Image Editor** | Transform existing images with natural language prompts |
| **Image Generator** | Create original images from text descriptions |
| **Multi-Image Edit** | Apply the same edit across multiple images at once |
| **Multi-Image Combine** | Merge 2+ images together with a guiding prompt |

### Core Capabilities

- **Drag & Drop Interface** — Intuitive upload with visual feedback
- **Multiple AI Models** — Choose from Gemini Flash 2.0, Exp-1206, Pro-002, Flash-8B
- **Aspect Ratio Control** — 1:1, 16:9, 9:16, 4:3, 3:4 per generation
- **Batch Processing** — Multiple slots per mode for parallel workflows
- **History Tracking** — All generations saved with timestamps and source tracking
- **Collection System** — Star and curate your favorites in a personal gallery
- **Full-Size Preview** — Click any image for an immersive modal view
- **Batch Download** — Export individual images or entire collections
- **Persistent Storage** — IndexedDB ensures your work survives browser sessions

---

## Available Models

| Model | Best For | Speed | Quality |
|-------|----------|-------|---------|
| Gemini Flash 2.0 | Fast iterations | ⚡⚡⚡ | ⭐⭐⭐ |
| Gemini Exp-1206 | Experimental features | ⚡⚡ | ⭐⭐⭐⭐ |
| Gemini Pro-002 | Highest quality | ⚡ | ⭐⭐⭐⭐⭐ |
| Gemini Flash-8B | Ultra-fast testing | ⚡⚡⚡⚡ | ⭐⭐ |

---

## Getting Started

### Option 1: Use the Live Version

**[https://m1w234.github.io/NanoBananaUnleashed/](https://m1w234.github.io/NanoBananaUnleashed/)**

### Option 2: Run Locally

1. Clone or download the repository
   ```bash
   git clone https://github.com/m1w234/NanoBananaUnleashed.git
   ```
2. Open `index.html` in your browser (double-click or serve with any local server)
3. Click the settings icon and add your API key
4. Start creating

### API Keys

You'll need at least one:
- [Google AI Studio](https://aistudio.google.com/app/apikey) — Gemini models (editing + generation)
- [OpenAI Platform](https://platform.openai.com/api-keys) — Vision models (analysis)

All keys are stored locally in your browser's LocalStorage. Nothing is sent anywhere except the respective AI provider APIs.

---

## Usage Guide

### Editing Images
1. Go to the **Image Editor** tab
2. Drag and drop an image or click to upload
3. Describe the change: "Make the sky purple", "Remove the background", "Watercolor style"
4. Click **Edit with AI**

### Generating Images
1. Go to the **Image Generator** tab
2. Describe what you want: "A futuristic city with flying cars"
3. Select aspect ratio and number of variations
4. Click **Generate**

### Multi-Image Editing
1. Go to **Multi-Image Edit**
2. Upload multiple images
3. Enter one prompt that applies to all of them
4. Process all at once

### Combining Images
1. Go to **Multi-Image Combine**
2. Upload 2+ source images
3. Describe how to merge them: "Blend these into a panorama"
4. Generate the combination

### Managing Your Work
- **History** — View all past generations with source images and prompts
- **Collection** — Save favorites by clicking the star icon
- **Download** — Save individual images or batch export
- **Preview** — Click any image for full-screen view

---

## Tech Stack

- **React 18** — Frontend framework (CDN-loaded, no build step)
- **Tailwind CSS** — Styling
- **Google Gemini API** — Image editing and generation
- **OpenAI Vision API** — Image analysis
- **IndexedDB** — Image persistence
- **LocalStorage** — Settings and preferences
- **Lucide React** — Icons

Single HTML file architecture — the entire app is self-contained with no build process required.

---

## Privacy & Security

- API keys stored locally in your browser's LocalStorage
- Images stored in IndexedDB on your device only
- No data sent to external servers except Google/OpenAI APIs for processing
- No tracking or analytics

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
- Some prompts may be filtered by safety settings — try rephrasing
- Switch to a different model
- Check your API quota/rate limits

---

## Customization

The app is a single HTML file, making it easy to modify:

- **Styling** — Edit Tailwind classes or add custom CSS in the `<style>` section
- **Models** — Update the `availableModels` array to add/remove AI models
- **Features** — React component structure makes extending straightforward

---

## Roadmap

- [ ] Style presets for common edits
- [ ] Prompt history and suggestions
- [ ] Video generation support
- [ ] Export/import collections
- [ ] Undo/redo functionality
- [ ] Image-to-image variations

---

## License

MIT License — see [LICENSE](LICENSE) file for details.

---

## Contact

**Michael Wong** — [Team Wong Hawaii](https://teamwonghawaii.com)

**Project Link**: [https://m1w234.github.io/NanoBananaUnleashed/](https://m1w234.github.io/NanoBananaUnleashed/)
