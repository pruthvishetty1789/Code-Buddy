# CodeBuddy 🧠💻

CodeBuddy is a minimalist, dark-themed code editor interface built with React. It features a live-editable code pane and a review output pane — ideal for developer tools, coding assessments, or preview interfaces.

## 🚀 Features

- 📝 Live-editable code panel
- 🤖 AI-powered review suggestions using Google Gemini API
- 🧾 Scrollable output/review section
- 🎨 Dark mode UI for comfortable coding
- 🖱️ Responsive layout with Flexbox
- 💡 Built entirely with React 

## 🤖 Gemini API Integration

CodeBuddy integrates with **Google Gemini API** to analyze and review the code written by the user in real time. It sends code snippets to the Gemini model and displays AI-generated feedback in the review panel.

> ⚠️ Requires a valid Gemini API key set in the backend `.env` file:
>
> ```env
> GEMINI_API_KEY=your_gemini_api_key_here
> ```

## 🛠️ Installation

```bash
# Clone the repository
git clone https://github.com/pruthvishetty1789/CodeBuddy.git

# --- Backend ---
cd CodeBuddy/backend
npm install
npm run dev

# --- Frontend ---
cd ../client
npm install
npm run dev
