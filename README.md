# 🧠 Universal CP Assistant

Your personal **Competitive Programming AI Assistant** that helps you solve, understand, and optimize problems from platforms like **LeetCode**, **Codeforces**, and **CodeChef** — right in your browser.

---

## ⚙️ Overview

The assistant integrates directly into your browser as a Chrome extension and connects to your deployed FastAPI backend (powered by the **Google Gemini API**).

You can:
- Ask for hints or explanations for coding problems  
- Get code solutions in Python, C++, or Java  
- Analyze time complexity and edge cases  
- Chat with the AI directly while solving problems  

---

## 🚀 Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/krishnaaa03/Coding_Assistant.git
```

### 2. Install Chrome Extension

1. Open Chrome and go to:
   ```
   chrome://extensions/
   ```
2. Turn on **Developer mode**
3. Click **Load unpacked**
4. Select the `extension/` folder from this repository

✅ The extension is now installed!

### 3. Test It Out

1. Go to **LeetCode**, **Codeforces**, or **CodeChef**
2. You'll see a "💬 CP Assistant" button appear on the screen
3. Click it and start chatting with your AI coding assistant!

---

## 🧰 Common Issues

| Issue | Possible Fix |
|-------|-------------|
| Extension not connecting | Check if your backend URL is correct and accessible |
| "CORS" or network error | Ensure your backend allows cross-origin requests (CORS middleware in FastAPI) |
| First request slow | Render's free tier sleeps after inactivity — wait ~30 seconds |

---

## 💡 Notes

- You don't need to run the backend locally, since it's already deployed.
- Any time you update your backend code on GitHub, Render auto-redeploys.
- Your `GOOGLE_API_KEY` remains safely stored as an environment variable in Render.

---

## 📦 Tech Stack

- **Backend:** FastAPI (Python) + Google Gemini API
- **Frontend:** Chrome Extension (JavaScript + HTML + CSS)
- **Deployment:** Render Cloud

---

## 👨‍💻 Author

**Srinivas Prabhu**  
🔗 GitHub: [@srinivas0721](https://github.com/srinivas0721)
