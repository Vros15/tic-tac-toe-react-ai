# 🎮 Tic-Tac-Toe (React + AI)

A modern, interactive Tic-Tac-Toe game built with **React** featuring an optional **AI opponent** powered by a lightweight minimax-style decision algorithm.

This project is designed to be **clean, reusable, and embeddable**, making it ideal for portfolios and future expansion.

---

## ✨ Features

- ✅ Player vs Player mode
- 🤖 Player vs AI mode (minimax-lite)
- 🔁 Reset game at any time
- 🎨 Clean, modern UI
- ⚛️ Built with React + Vite
- 🧩 Component-based and reusable
- 🚀 Ready for embedding in other projects

---

## 🧠 AI Behavior

The AI opponent uses a **lightweight minimax-inspired strategy**:

- Always takes a winning move if available
- Blocks opponent winning moves
- Prefers center and corners
- Plays instantly (no delays or API calls)

This keeps gameplay challenging without being computationally heavy.

---

## 🛠️ Tech Stack

- **React**
- **Vite**
- **JavaScript (ES6+)**
- **CSS**

No backend required — runs entirely in the browser.

---

## 📦 Installation & Local Development

```bash
# Clone the repo
git clone https://github.com/Vros15/tic-tac-toe-react-ai.git

# Enter the project folder
cd tic-tac-toe-react-ai

# Install dependencies
npm install

# Start the dev server
npm run dev
Then open:

arduino
Copy code
http://localhost:5173
🔌 Reuse as a Component
The game logic lives in:

bash
Copy code
src/components/TicTacToe.jsx
You can import it into any React project:

jsx
Copy code
import TicTacToe from "./components/TicTacToe";

function App() {
  return <TicTacToe />;
}
🌐 Live Demo
(Coming soon — deployed via Vercel)

📁 Project Structure
css
Copy code
src/
 ├─ components/
 │   └─ TicTacToe.jsx
 ├─ App.jsx
 ├─ main.jsx
 └─ index.css
📄 License
MIT License — free to use, modify, and distribute.

👤 Author
Victor Rosario
🌐 https://roscreations.com
🐙 https://github.com/Vros15