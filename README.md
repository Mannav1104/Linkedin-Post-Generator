


https://github.com/user-attachments/assets/501164db-327f-4273-aced-69c162f78bf2


# 🌿 Vanam AI Post Generator
**Vanam AI** is a simple, powerful, single-page web application that uses Generative AI (Groq & Llama 3.1) to help you write new LinkedIn posts that perfectly match your unique writing style.

This is a **zero-install** project — it runs entirely in your browser from a single `index.html` file.

---

## ✨ Features

- **Define Your Voice**  
  Paste in your past LinkedIn posts for the AI to learn your tone, vocabulary, and structure.

- **AI-Powered Topic Suggestions**  
  Don’t know what to write? The AI can suggest 3 new topics based on your past posts.

- **Refine Your Post**  
  Control the output with simple options for:
  - **Post Length**: Short, Intermediate, Full Long Text  
  - **Post Tone**: Default, Formal, Casual

- **Ultra-Fast Generation**  
  Uses the **Groq API** (running `llama-3.1-8b-instant`) for near-instant results.

- **Utility Features**
  - ✅ Copy to Clipboard  
  - ✅ Download as PDF  
  - ✅ Responsive, animated UI with a luxury **mocha green** theme

---

## 🛠 Technologies Used

### Front-End
- **HTML5** — Structure of the application  
- **Tailwind CSS** — Styling via CDN  
- **JavaScript (ES6+)** — Application logic, API calls, DOM manipulation

### Generative AI
- **Groq API** — Free, high-speed AI inference  
- **Llama 3.1 8B Instant** — The Large Language Model (LLM) powering the writing

### Libraries
- **jsPDF** — Enables "Download PDF" functionality (loaded via CDN)

---

## 🚀 How to Run This Project

This project is designed for simplicity. You don’t need to install Node.js, npm, Python, or any backend.

### Step 1: Get Your Free Groq API Key
1. Visit the [Groq Console](https://console.groq.com/keys)
2. Sign up using Google or GitHub
3. Go to **API Keys** and click **+ Create API Key**
4. Name your key (e.g., `vanam-ai-project`) and click **Create**
5. Copy the key that starts with `gsk_...`

---

### Step 2: Add Your Key to `index.html`
1. Download or clone this repository
