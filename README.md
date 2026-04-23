# NOCTUARY — The Literature-First AI

> *A journal of night thoughts. For the ones who write in the dark.*

Noctuary is the first AI built literature-first — not for coders, not for marketers, but for **writers**. Novelists, memoirists, horror architects, worldbuilders, and anyone who takes the craft of storytelling seriously.

## Five Personalities

- 🧙 **The Sage** — Warm mentor & writing coach
- 🗡️ **The Red Quill** — Ruthless developmental editor
- ⚡ **The Muse** — Wild creative collaborator
- 🔮 **The Architect** — Structural & thematic analyst
- 📜 **The Lorekeeper** — Worldbuilding & lore specialist

## Setup Instructions

### Step 1: Get a Gemini API Key (Free)

1. Go to [https://aistudio.google.com/apikey](https://aistudio.google.com/apikey)
2. Sign in with your Google account
3. Click **"Create API Key"**
4. Copy the key

### Step 2: Add Your API Key

1. Open `index.html`
2. Find this line near the top of the `<script>` section:
   ```
   const API_KEY = 'YOUR_GEMINI_API_KEY_HERE';
   ```
3. Replace `YOUR_GEMINI_API_KEY_HERE` with your actual API key
4. Save the file

### Step 3: Deploy to GitHub Pages

1. Go to your GitHub repository
2. Upload `index.html`
3. Go to **Settings** → **Pages**
4. Under "Source", select **Deploy from a branch**
5. Select **main** branch and **/ (root)** folder
6. Click **Save**
7. Wait 1-2 minutes — your site will be live at `https://noctuary-ai.github.io/YOUR-REPO-NAME/`

## Free Tier Limits

Noctuary runs on Google's Gemini 2.5 Flash (free tier):
- ~250 requests per day
- 10 requests per minute
- 1 million token context window (supports full manuscripts)

## Features

- 📎 **Manuscript upload** — Upload .txt files for full analysis
- 🎭 **Five distinct AI personalities** for different writing needs
- 📚 **Deep literary knowledge** — King, Jackson, Tolkien, Morrison, McCarthy, VanderMeer, Rowling, Walls, Le Guin, Lamott, and more
- 🌙 **Royal purple arcane aesthetic** — because writers deserve beautiful tools
- 💬 **Conversation memory** — maintains context within a session

---

*Built for serious writers. Powered by Gemini. Designed in the dark.*
