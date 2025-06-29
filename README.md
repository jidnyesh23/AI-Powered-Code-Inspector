<h1 align="center">
  🧠 IntelliCode AI
  <br/>
  <img src="https://media.giphy.com/media/QssGEmpkyEOhBCb7e1/giphy.gif" width="80" />
</h1>

<p align="center">
  <strong>AI-powered code analyzer</strong> built with React.js, Express.js, and Google Gemini API.<br/>
  Detect bugs, suggest fixes, and optimize code in real-time.
</p>

---

## 🚀 Overview

**IntelliCode AI** is a smart developer tool that uses AI to understand and analyze code.  
It instantly detects bugs, suggests fixes, and recommends performance improvements using **Google Gemini API**, all within an interactive web interface.

---

## ✨ Features

- 🔍 Instant bug & issue detection
- 🧠 AI-powered fix suggestions
- ⚙️ Performance & optimization tips
- 🖥️ Clean, developer-friendly interface
- ⚡ Real-time response as you type or paste code

---

## ⚙️ Tech Stack

| Frontend  | Backend     | AI Layer            |
|-----------|-------------|---------------------|
| React.js  | Express.js  | Google Gemini API   |

---

## 🛠️ Quick Start (All-in-One Setup)

```bash
# Clone the repo
git clone https://github.com/jidnyesh23/AI-Powered-Code-Inspector.git
cd AI-Powered-Code-Inspector

# Install backend dependencies
cd server
npm install

# Add Gemini API Key
echo "GEMINI_API_KEY=your_gemini_api_key_here" > .env

# Start backend server
npm start &
cd ..

# Install frontend dependencies
cd client
npm install

# Start frontend
npm start
