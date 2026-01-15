# ✨ AI Prompt Improver v2

<div align="center">

![Project Banner](https://img.shields.io/badge/AI-Prompt_Improver-667eea?style=for-the-badge&logo=openai&logoColor=white)
![Status](https://img.shields.io/badge/Status-Active-success?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)

**Transform your basic prompts into professional, high-quality inputs for ChatGPT, Claude, Midjourney, and more!**

</div>

---

## 🚀 Features

- **🎨 Staggered Grid UI**: A stunning, responsive animated background effect.
- **🤖 Multi-Model Support**: Specialized optimization for ChatGPT, Claude, Midjourney, DALL-E, Stable Diffusion, and more.
- **✨ Auto-Fill Use Case**: AI intelligently detects the intended use case for your prompt.
- **🔒 Jailbreak Mode**: Advanced mode for security research and unrestricted prompt engineering testing.
- **⚡ Fast & Client-Side**: Built with Vanilla JS and Anime.js for smooth performance.

---

## 🛠️ Installation & Setup

This is a **client-side web application**, meaning you don't need to install Node.js or Python to run it!

### 1. Download the Files
Clone this repository or download the ZIP file.

### 2. Set Up Your API Key
To make the AI features work, you need a **Groq API Key** (it's free!).

1. Open `app.js` in any text editor (Notepad, VS Code, etc.).
2. Find the line near the top that looks like this:
   ```javascript
   const API_KEY = "YOUR_API_KEY_HERE";
   ```
3. Replace `"YOUR_API_KEY_HERE"` with your actual API key:
   ```javascript
   const API_KEY = "gsk_..."; // Your key goes here
   ```
   > **Note:** Never commit your real API key to GitHub if you make the repo public!

### 3. Run the App
Simply double-click `index.html` to open it in your browser. That's it! 🎉

---

## 📸 How to Use

### Step 1: 🎯 Select Your AI
Enter the name of the AI model you are using (e.g., "ChatGPT", "Midjourney", "Claude"). The app automatically detects best practices for that specific model.

### Step 2: ✍️ Enter Your Prompt
Type your basic prompt into the text area.
> *Example: "Make a logo for a coffee shop"*

### Step 3: ✨ Auto-Fill Use Case (Optional)
Click the **✨ Auto-Fill** button. The AI will analyze your prompt and determine the best context (e.g., "Minimalist branding for a modern urban coffee shop targeting millennials").

### Step 4: 🚀 Improve!
Click **Improve Prompt**. Watch as your simple request is transformed into a sophisticated, professional-grade prompt structure.

### 🔒 Jailbreak Mode (Advanced)
Toggle the **Jailbreak Mode** button in the bottom right corner to switch to Red Team/Security Research mode. This generates prompts designed to test safety filters.

---

## 📂 Files to Upload

If you are uploading this to GitHub, simply upload these files:

- `index.html` (The main page)
- `styles.css` (The styling and animations)
- `app.js` (The logic and API connection)
- `README.md` (This file!)

---

## 💫 Credits

Built with ❤️ using:
- **Anime.js** for the beautiful grid animations
- **Groq API** for lightning-fast AI inference
- **FontAwesome** references
