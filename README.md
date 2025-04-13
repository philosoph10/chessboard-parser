# ♟️ Chessboard Parser with Chesscog

## 📖 Overview

This project contains a Jupyter Notebook that demonstrates how to extract and analyze a chessboard position from a photo.

The logic is broken into two main steps:
1. **Parse the chess position** from the image.
2. **Analyze the position** to figure out who is winning and suggest the best move.

The core functionality is powered by [`chesscog`](https://github.com/georg-wolflein/chesscog), a chessboard recognition library.

---

## 📂 Notebook

You can find the main notebook here:
`./notebooks/chess-parser.ipynb`

This notebook walks through:
- Loading and preprocessing a chessboard image.
- Inferring board state using computer vision.
- Using a chess engine to evaluate and suggest optimal moves.

---

## ⚙️ Setup Instructions

### ✅ Recommended Python Version
- **Python 3.10**

### 📦 Installation

Make sure you have [`poetry`](https://python-poetry.org/) installed.

Then, to install dependencies for `chesscog`, run:

```bash
cd chesscog
poetry install
```

> **Note:** You do **not** need to clone the `chesscog` repository — it is already included in the project.

---

## 👨‍💻 Developer

**Yur-Liubomysl Dekhtiar**  
[GitHub Profile](https://github.com/philosoph10)

---

## 🧠 Credits

- 🧩 **Chessboard recognition:** [chesscog](https://github.com/georg-wolflein/chesscog)  
- 🧠 **Chess engine evaluation:** [Stockfish](https://stockfishchess.org/)