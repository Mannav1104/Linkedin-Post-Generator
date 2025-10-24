Vanam AI Post Generator
This is a simple, powerful, single-page web application that uses Generative AI (Groq & Llama 3.1) to help you write new LinkedIn posts that perfectly match your unique writing style.
It's a "zero-install" project—it runs entirely in your browser from a single index.html file.
Features
Define Your Voice: Paste in your past posts for the AI to learn your tone, vocabulary, and structure.
AI-Powered Topic Suggestions: Don't know what to write? The AI can suggest 3 new topics based on your past posts.
Refine Your Post: Control the output with simple options for Post Length (Short, Intermediate, Full Long Text) and Post Tone (Default, Formal, Casual).
Ultra-Fast Generation: Uses the Groq API (running llama-3.1-8b-instant) for near-instant results.
Utility Features:
Copy to Clipboard: Instantly copy the generated post.
Download as PDF: Save your post as a PDF for your records.
Luxury UI: A clean, responsive, and animated interface with a luxury "mocha green" theme.
Technologies Used
Front-End:
HTML5: The structure of the application.
Tailwind CSS: For all styling, loaded via a CDN.
JavaScript (ES6+): For all application logic, including API calls and DOM manipulation.
Generative AI:
Groq API: Provides the free, high-speed AI inference.
Llama 3.1 8B Instant: The specific (and free) Large Language Model (LLM) doing the writing.
Libraries:
jsPDF: Used for the "Download PDF" functionality, loaded via a CDN.
🚀 How to Run This Project
This project is designed for simplicity. You don't need to install any software (like Node.js, npm, or Python).
Step 1: Get Your Free Groq API Key
Go to the Groq Console: https://console.groq.com/keys
Sign up for a free account (you can use your Google or GitHub account).
Once on the "API Keys" page, click "+ Create API Key".
Name your key (e.g., "vanam-ai-project") and click "Create".
Copy the key that starts with gsk_...
Step 2: Add Your Key to index.html
Download or clone this repository.
Open the index.html file in any code editor (like VS Code, Sublime Text, or even Notepad).
Scroll down to line 382 (or find the line const API_KEY = "";).
You will see this line:
const API_KEY = ""; // <-- PASTE YOUR GROQ API KEY HERE


Paste your Groq API key (the one you just copied) inside the quotes:
const API_KEY = "gsk_YourPersonalKeyGoesHere..."; // <-- PASTE YOUR GROQ API KEY HERE


Save the index.html file.
Step 3: Run the Application
Just double-click the index.html file to open it in your favorite web browser (like Chrome, Firefox, or Edge).
That's it! The application will load and be fully functional.
	
