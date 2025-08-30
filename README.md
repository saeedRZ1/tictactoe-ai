[README (1).md](https://github.com/user-attachments/files/22061278/README.1.md)
# 🎮 Tic Tac Toe AI with Minimax

![Python](https://img.shields.io/badge/python-3.x-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen)

---

## 📑 Table of Contents
- [Demo](#-demo)
- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [Installation](#️-installation)
- [How to Run](#-how-to-run)
- [Project Structure](#-project-structure)
- [Future Improvements](#-future-improvements)
- [License](#-license)
- [Contributing](#-contributing)

---

## 🎥 Demo
<p align="center">
  <img src="https://github.com/user-attachments/assets/948669b0-8ae5-4a10-b86c-35192ed00ba2" width="400" alt="Tic Tac Toe Demo"/>
</p>

An AI-powered Tic Tac Toe game that uses the **Minimax algorithm** to make optimal moves.  
Play in the terminal: **You (X) vs AI (O)**. The AI plays optimally, so you cannot beat it (best case: draw).

---

## ✨ Features
- Human vs AI gameplay
- AI implemented using **Minimax algorithm**
- Detects game-over conditions: win, lose, or draw
- Simple terminal UI with numbered board
- Clean, modular code — easy to extend to GUI or web API

---

## 🛠 Tech Stack
- **Python 3**
- **Minimax Algorithm**

---

## ⚙️ Installation
Clone the repository and make sure Python 3 is installed:
```bash
git clone https://github.com/your-username/tictactoe-ai.git
cd tictactoe-ai
```
No external dependencies required. Just use Python's standard library.

---

## ▶️ How to Run
```bash
# Ensure you're in the project root
python main.py
```

---

## 📂 Project Structure
```
tictactoe-ai/
│
├── tictactoe/
│   ├── __init__.py
│   ├── ai.py          # Minimax AI logic
│   ├── game.py        # Game loop & terminal I/O
│   └── utils.py       # Winner checks & helpers
│
├── main.py            # Entry point
└── README.md
```

---

## 🚀 Future Improvements
- Add a GUI version using Pygame or a simple web UI (Flask/FastAPI)
- Add AI vs AI mode
- Introduce difficulty levels (Easy/Medium/Hard)

---

## 📜 License
This project is licensed under the MIT License - see the LICENSE file for details.

---

## 🤝 Contributing
Contributions are welcome! Feel free to fork the repository and submit a pull request with your improvements.

---

⭐ If you like this project, please **star the repo**! ⭐
