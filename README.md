# 🛡️ Scam Scanner AI

An advanced, AI-powered cybersecurity single-page application built for **PromptWars × Gen AI Club** (Presidency University in collaboration with Google for Developers and Hack2Skill).

**Scam Scanner AI** helps job seekers and renters instantly analyze suspicious appointment letters, emails, URLs, and deposit traps using the intelligence of Google Gemini[cite: 1].

---

## 🚀 Core Features
* **Zero-Setup Architecture:** Completely contained within a single `index.html` file using Tailwind CSS via CDN and vanilla JavaScript—requires no Node.js, backend servers, or external build tools.
* **Direct Google Gemini AI Integration:** Leverages the Gemini API with specialized cybersecurity system prompts to evaluate recruitment and rental fraud patterns.
* **Dynamic Threat Scoring (0–100%):** Calculates an intelligent risk metric accompanied by an animated progress gauge and risk-level badges (Low, Medium, High, Critical).
* **Detailed Intelligence Breakdown:** Automatically extracts specific red flags (such as upfront payment demands, crypto requests, or mismatched domains) and outputs actionable safety recommendations.
* **Secure Client-Side API Handling:** Safely stores your Google Gemini API key locally in the browser session via `localStorage`.

---

## 🛠️ Tech Stack
* **Frontend:** HTML5, Tailwind CSS (via CDN), Vanilla JavaScript
* **AI Engine:** Google Gemini API (`gemini-1.5-flash`)

---

## ⚙️ How to Run Locally
1. Download or clone this repository to your local machine.
2. Double-click the `index.html` file to open it instantly in any modern web browser (Chrome, Edge, Firefox, Safari).
3. Enter your **Google Gemini API Key** (get a free one from [Google AI Studio](https://aistudio.google.com/)) and click **Save Key**.
4. Paste the suspicious job offer text or URL into the scanner box and click **Analyze Threat**.

---

## 🔒 Security Notice
* **No hardcoded credentials:** API keys are never hardcoded or pushed to public repositories[cite: 1]. Keys are securely handled on the client side via user input.