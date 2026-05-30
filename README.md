# Senku - All-in-One AI Assistant

An elegant, fully functional AI-powered web app built with vanilla HTML, CSS, and JavaScript.

## 🌟 Features

### 4 Powerful Tabs:
1. **Chat** — Full back-and-forth conversation with Claude AI, maintains conversation history
2. **Summarizer** — Paste any text and get summaries in three styles: bullet points, short paragraph, or detailed
3. **Writer** — Generate content (emails, captions, essays, bios, cover letters) in different tones (professional, casual, friendly, persuasive)
4. **Idea Generator** — Get creative ideas (5, 10, or 15) with one-line explanations

## 🎨 Design

- **Clean, Modern UI** — Flat design with no gradients or shadows
- **Purple Theme** — Primary color: `#534AB7`, Hover: `#7F77DD`
- **Fully Responsive** — Works seamlessly on desktop, tablet, and mobile
- **Loading States** — Visual feedback while waiting for AI responses
- **Error Handling** — Graceful error messages if something goes wrong

## 🚀 Quick Start

### Option 1: Use Live (Recommended)
Open in your browser: **[https://jainav090-boop.github.io/Senku/](https://jainav090-boop.github.io/Senku/)**

### Option 2: Local Setup
1. Clone or download this repository
2. Open `index.html` in your web browser
3. Add your Anthropic API key (see below)

## 🔑 API Key Setup

1. Get your API key from [Anthropic Console](https://console.anthropic.com/)
2. Open `index.html` in a text editor
3. Find this line in the `<script>` section:
   ```javascript
   const API_KEY = 'YOUR_ANTHROPIC_API_KEY_HERE';
   ```
4. Replace with your actual key:
   ```javascript
   const API_KEY = 'sk-ant-v7-xxxxxxxxxxxxxxxxxxxxxxx';
   ```
5. Save and refresh the page

## 📋 Technical Details

- **No Dependencies** — Single HTML file, no frameworks or build tools
- **AI Model** — Claude Sonnet 4 (`claude-sonnet-4-20250514`)
- **API** — Anthropic Claude API (`https://api.anthropic.com/v1/messages`)
- **Vanilla JavaScript** — Pure JS, no jQuery or libraries

## 🎯 System Prompt

All AI calls use this system prompt:
> "You are Senku, a helpful all-in-one AI assistant created by Jainav. Be concise, friendly, and helpful."

## 📱 Browser Support

Works on all modern browsers:
- Chrome/Edge
- Firefox
- Safari
- Mobile browsers

## 🛠️ Development

The entire app is in `index.html` — edit directly for customization:
- Modify colors in `:root` CSS variables
- Adjust AI prompts in the JavaScript functions
- Change max tokens or model in `API_URL` configuration

## 📄 License

This project is open source and available for personal and commercial use.

## 👤 Created by

**Jainav** — [GitHub](https://github.com/jainav090-boop)

---

**Made with ❤️ using Claude AI**
