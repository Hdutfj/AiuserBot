# 🤖 AI Assistant - John

Welcome to **John**, your personal AI assistant built using **Chainlit**, **Python**, and **GitHub OAuth login**. Aania offers warm, intelligent, and conversational responses to users in a secure, authenticated chat interface.

---

## 🚀 Features

- ✨ Conversational AI assistant powered by Gemini/OpenAI models
- 🔒 Secure login system using **GitHub OAuth only**
- 🧠 Remembers chat history during session
- ❤️ Friendly, personalized, and context-aware responses
- 🎉 Special reactions to keywords like "love you", "done", etc.

---

## 🖼️ Screenshots

| GitHub Login Page | AI Chat Interface |
|-------------------|------------------|
| ![Login](./screenshots/github-login.png) | ![Chat](./screenshots/chat-interface.png) |

---

## 🧩 Tech Stack

- **Python**
- **Chainlit**
- **OAuth2 (GitHub)**
- **dotenv** for environment management
- **Gemini API / OpenAI compatible model**

---

## 🔐 Authentication

Currently, login is **only available via GitHub**.

### GitHub OAuth Setup

1. Go to [GitHub Developer Settings](https://github.com/settings/developers).
2. Create a new **OAuth App**:
   - Homepage: `http://localhost:8000`
   - Callback URL: `http://localhost:8000/callback`
3. Copy the **Client ID** and **Client Secret** into a `.env` file.

```env
OAUTH_GITHUB_CLIENT_ID=your_client_id_here
OAUTH_GITHUB_CLIENT_SECRET=your_clien
