# 💬 JavaScript Chatbot Web App

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,25,13&height=210&section=header&text=JavaScript%20Chatbot%20Web%20App&fontSize=44&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=Build%20Smart%20Conversations%20with%20Pure%20JavaScript&descAlignY=56&descSize=18" width="100%"/>

<br/>

[![Version](https://img.shields.io/badge/version-2.7.0-FF6B9D?style=for-the-badge&logo=semanticrelease&logoColor=white)](https://github.com)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES2023-C084FC?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org)
[![License](https://img.shields.io/badge/license-MIT-A855F7?style=for-the-badge&logo=opensourceinitiative&logoColor=white)](LICENSE)
[![Size](https://img.shields.io/badge/size-%3C%2015kb-EC4899?style=for-the-badge&logo=javascript&logoColor=white)](https://github.com)

<br/>

### 🤖 A lightweight, framework-free chatbot that runs entirely in the browser

*⚡ Zero Dependencies • 🎨 Beautiful UI • 🧠 Smart Responses • 🔌 LLM-Ready*

<br/>

<a href="https://share.google/keiSlXMtQVNtAlEY1">
  <img src="https://img.shields.io/badge/🚀_LIVE_DEMO-FF6B9D?style=for-the-badge&logo=googlechrome&logoColor=white&labelColor=CC557D" alt="Live Demo" height="45"/>
</a>
&nbsp;&nbsp;
<a href="https://share.google/keiSlXMtQVNtAlEY1">
  <img src="https://img.shields.io/badge/📥_GET_CODE-C084FC?style=for-the-badge&logo=github&logoColor=white&labelColor=9A69CA" alt="Get Code" height="45"/>
</a>
&nbsp;&nbsp;
<a href="https://share.google/keiSlXMtQVNtAlEY1">
  <img src="https://img.shields.io/badge/📚_DOCS-A855F7?style=for-the-badge&logo=readthedocs&logoColor=white&labelColor=8644C5" alt="Docs" height="45"/>
</a>

</div>

<img width="739" height="415" alt="images (3)" src="https://github.com/user-attachments/assets/e22d516f-665f-46e2-85da-eea0445ce1c6" />


<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🌟 About

**JavaScript Chatbot Web App** is a complete, ready-to-use chatbot interface built with **vanilla JavaScript** — no React, no Vue, no frameworks. Just clean, modern ES2023 code that runs directly in the browser.

It ships with a built-in **rule-based response engine** for immediate use, but it's designed to plug into **any LLM API** (OpenAI, Anthropic, Ollama, etc.) in just a few lines of code.

> 💡 **Perfect for:** Portfolio projects, learning how chat UIs work, embedding a lightweight assistant on a website, or prototyping an LLM frontend.

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🎯 Key Features

<div align="center">

| 💬 **Chat UI** | 🧠 **Response Engine** | 🔌 **LLM-Ready** |
|:---:|:---:|:---:|
| Clean bubbles, typing<br/>indicator & timestamps | Rule-based bot<br/>out of the box | Swap in OpenAI, Claude<br/>or Ollama in minutes |

| 🎨 **Themeable** | 💾 **Local History** | 📱 **Responsive** |
|:---:|:---:|:---:|
| CSS variables for<br/>colors, fonts & radius | Persists chats via<br/>`localStorage` | Works on mobile,<br/>tablet & desktop |

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🏆 Why This Project

<div align="center">

| 💎 **Advantage** | 📝 **Description** |
|:---|:---|
| ⚡ **Zero Dependencies** | No npm install, no build step — just open `index.html` and it works |
| 🎨 **Modern UI** | Beautiful, smooth animations and a clean design that feels native |
| 🧠 **Dual-Mode Engine** | Use the built-in rule bot, or connect to any LLM via a single config flag |
| 📦 **Tiny Footprint** | Under 15kb total — faster than any chat widget on the market |
| 💾 **Full History** | Chats are saved locally so users never lose a conversation |
| 🎯 **Beginner-Friendly** | Extremely readable code — ideal for learning and forking |

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🎬 Chat Preview

<div align="center">

```ascii
╔══════════════════════════════════════════════════╗
║  💬  JavaScript Chatbot  v2.7.0                  ║
╠══════════════════════════════════════════════════╣
║                                                  ║
║  🤖  Hi there! How can I help you today?         ║
║                                    10:24 AM  ✓   ║
║                                                  ║
║  👤  Tell me a fun fact about JavaScript         ║
║                                    10:25 AM      ║
║                                                  ║
║  🤖  JavaScript was created in just 10 days!     ║
║      Brendan Eich built it in May 1995 — and     ║
║      it became the language of the web. 🚀       ║
║                                    10:25 AM  ✓   ║
║                                                  ║
║  ┌────────────────────────────────────────────┐  ║
║  │ Type a message...                    [→]   │  ║
║  └────────────────────────────────────────────┘  ║
╚══════════════════════════════════════════════════╝
```

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🧩 Project Structure

```
💬 javascript-chatbot-web-app/
├── 🎯 src/
│   ├── chat/                  # Chat UI & rendering
│   │   ├── chat.js
│   │   └── messages.js
│   ├── engine/                # Response engine
│   │   ├── rule-bot.js
│   │   └── llm-adapter.js
│   ├── storage/               # localStorage history
│   └── theme/                 # CSS variable theming
├── 🎨 styles/
│   └── main.css
├── 🌐 index.html
├── 🧪 tests/                  # Vitest unit tests
└── 📖 docs/                   # Usage & LLM setup guide
```

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🛠️ Tech Stack

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=for-the-badge&logo=vitest&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🤝 Community

Want to add a feature? Found a bug? Share your chatbot fork!

<div align="center">

<a href="https://share.google/keiSlXMtQVNtAlEY1">
  <img src="https://img.shields.io/badge/💬_Join_Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" height="35"/>
</a>
<a href="https://share.google/keiSlXMtQVNtAlEY1">
  <img src="https://img.shields.io/badge/🐞_Report_Issue-FF6B9D?style=for-the-badge&logo=github&logoColor=white" height="35"/>
</a>
<a href="https://share.google/keiSlXMtQVNtAlEY1">
  <img src="https://img.shields.io/badge/⭐_Star_Repo-A855F7?style=for-the-badge&logo=github&logoColor=white" height="35"/>
</a>

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 📜 License

Distributed under the **MIT License**. See [`LICENSE`](LICENSE) for details.

<br/>

<div align="center">

### 💬 Made with 💜 by the JS Chatbot Team

*If this project helped you build something cool — star the repo!*

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,25,13&height=120&section=footer" width="100%"/>

</div>
