# play-chess-with-ai
An interactive chess game developed in Python using Pygame, featuring a strong AI opponent based on the Minimax algorithm with Alpha-Beta pruning and positional evaluation.
# ♟️ Pygame Chess AI

A Python-based Chess game built with **Pygame** featuring an AI opponent powered by the **Minimax Algorithm** with **Alpha-Beta Pruning**. The project uses the **python-chess** library for chess rules and move validation while implementing an intelligent evaluation function for strategic gameplay.

---

## 📌 Features

- ♟️ Interactive chessboard built using Pygame
- 🤖 AI opponent using Minimax Algorithm
- ⚡ Alpha-Beta Pruning for optimized search
- 📊 Enhanced board evaluation with:
  - Material evaluation
  - Piece-square tables
  - Mobility evaluation
  - King safety
  - Pawn structure analysis
  - Endgame detection
- ✅ Legal move generation using `python-chess`
- 🎯 Automatic pawn promotion to Queen
- 🟩 Highlights selected pieces and legal moves
- 🏁 Checkmate, stalemate, and draw detection

---

## 🛠️ Technologies Used

- Python 3
- Pygame
- python-chess

---

## 📂 Project Structure

```
.
├── chess_ai.py          # Main application
├── README.md
```

---

## 🚀 Installation

### Clone the repository

```bash
git clone https://github.com/dolly-singla/pygame-chess-ai.git
cd pygame-chess-ai
```

### Install dependencies

```bash
pip install pygame python-chess
```

## ▶️ Run the Project

```bash
python chess_ai.py
```

---

## 🎮 How to Play

- You play as **White**.
- Click on one of your pieces to select it.
- Click on a highlighted destination square to move.
- The AI automatically responds after your move.
- The game ends when checkmate, stalemate, or another draw condition is reached.

---

## 🧠 AI Algorithm

The AI uses:

- Minimax Search
- Alpha-Beta Pruning
- Move Ordering
- Piece-Square Tables
- Material Evaluation
- Mobility Analysis
- King Safety Evaluation
- Pawn Structure Analysis
- Endgame Evaluation

These techniques significantly improve both playing strength and search efficiency.

---

## 🔮 Future Improvements

- Adjustable AI difficulty levels
- Opening book
- Move history panel
- Undo/Redo moves
- Castling animation
- Multiple promotion choices
- Game timer
- Sound effects
- Multiplayer mode
- Better UI and animations

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a feature branch

```
git checkout -b feature-name
```

3. Commit your changes

```
git commit -m "Add new feature"
```

4. Push the branch

```
git push origin feature-name
```

5. Open a Pull Request

---

## 👨‍💻 Author

**Dolly Singla**

GitHub: https://github.com/dolly-singla

---

⭐ If you found this project useful, consider giving it a star!
