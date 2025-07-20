# 🧠 JARVIS-MARK5 (Beginner Edition)

Welcome to **JARVIS-MARK5**, a voice-powered AI assistant inspired by Iron Man's JARVIS.  
This version is simplified for **kids and beginners**, with a full walkthrough website, friendly design, and no coding skills required!

---
<p align="center">
  <a href="https://aaryanbanskota.github.io/jarvis-ai/" target="_blank">
    <img src="https://img.shields.io/badge/📥%20Click%20Here%20to%20Download%20%26%20Run%20Guide-blue?style=for-the-badge" alt="need help">
  </a>
</p>

## 📥 How to Download & Run (Super Easy)

> 🧒 This section is written for people with **zero experience** in coding.

### 🖱️ Step 1: Download the Project

1. Go to this GitHub page.
2. Click the green **Code** button.
3. Choose **Download ZIP**.
4. Right-click the ZIP file and select **Extract All**.

### 🧰 Step 2: Install Python (Only Once)

1. Download Python from [python.org](https://www.python.org/downloads/).
2. While installing, **tick the checkbox that says “Add Python to PATH”**.
3. Click Install.

### 📦 Step 3: Install Requirements

1. Open the folder where you extracted the project.
2. Click the address bar at the top of the folder, type `cmd` and press Enter.
3. A black terminal will open.
4. Copy and paste this:

```bash
pip install -r requirements.txt
```

> If something fails, try installing these manually:  
> `pip install groq ollama gradio_client httpx pydantic`

---

## ⚙️ Configuration  
Update your `config/config.json` and `backend/AI/Perplexica/config.toml` with your API keys.

> Don’t forget to install the model file from the original repo or site and place it in the correct location.

---

## 🚀 Usage

```bash
python jarvis.py
```

JARVIS will start listening to you. You can now give commands like:

- “Search for Mount Everest”  
- “Create a presentation about Black Holes”  
- “Clone repository openai/gpt-4”

---

## 🔌 Modules & Extensions  

This version includes:

- ✅ Perplexica: Search engine using GPT + Groq  
- ✅ PowerPoint Generator  
- ✅ Voice-to-Text & Text-to-Voice  
- ✅ Image Generator  
- ✅ GitHub Integration  
- ✅ Task Automation & Assistant Mode  

More extensions can be added. Check the `extensions/` folder.

---

## 🧠 Advanced Features  

- Real-time AI processing  
- Embedding-based semantic search  
- LLM chaining and planning (via automodel)  
- Plugin-based system for new skills  

---

## 🛠️ Performance Tips  

- Use a GPU-enabled system for faster response.  
- Store frequently used answers in cache.  
- Prefer Groq or local LLMs for speed.  

---

## 🧷 Troubleshooting  

If something breaks, don’t worry! Check:

- ✅ Python version: 3.8+  
- ✅ Model file placed in correct folder  
- ✅ `.env` or config files have valid API keys  
- ✅ PostgreSQL installed and configured correctly  

If you still have issues, visit the website for full visual help.

---

## 👤 Contributing  

Want to add your own modules or make the UI cooler?  
Fork this project and submit a pull request!

---

## 📅 Roadmap  

- Mobile interface  
- Web dashboard for controlling Jarvis remotely  
- Home automation via MQTT  
- App for Android and iOS  
- Support for local Ollama/LM Studio models  

---

## ❓ FAQ

**Can kids use this?**  
Yes! This version was made simple enough for children to install with a website walkthrough.

**Does it need the internet?**  
Yes, most features like GPT and Groq require an internet connection.

**Is it free to use?**  
Yes, but some APIs may have free or paid plans.

---

## 📜 License  
MIT License – free for personal and commercial use.

---

## 🙏 Acknowledgements  

Original codebase by [@Likhithsai2580](https://github.com/Likhithsai2580) –  
💡 *Big thanks for creating the powerful JARVIS system!*  

Website version and beginner guide packaged by **Aaryan**.  
Now even kids can use JARVIS! 🧒⚡

---
