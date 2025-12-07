# Python Chess: Engine & GUI ♟️

![Python](https://img.shields.io/badge/python-blue?logo=python)
![Pygame](https://img.shields.io/badge/GUI-Pygame-green?logo=sdl)
![Manager](https://img.shields.io/badge/dependency-uv-purple)
![License](https://img.shields.io/badge/license-MIT-grey)

A fully functional, rule-compliant Chess game written in Python. It features a custom-built engine with a **Pygame** graphical user interface and smooth piece animations.

Unlike simple tutorials, this project implements the complete set of Chess rules, including complex edge cases.

## ✨ Features
* **Complete Ruleset:** Fully supports **Castling** and **En Passant** captures.
* **Interactive Promotion:** When a pawn reaches the end, a options appear to let the player choose the promotion piece (Queen, Rook, Bishop, or Knight).
* **Local Multiplayer:** 2-player hot-seat mode.
* **Smooth Animations:** Pieces glide to their target squares rather than teleporting.
* **Modern Tooling:** Project managed with `uv` for fast dependency resolution.

## 📸 Gameplay
<p align="center">
  <img src="https://github.com/user-attachments/assets/a3a6cc1d-d3a4-4dff-82ea-5281fac1c22d" alt="Chess Gameplay" width="400">
</p>

## 🛠️ Tech Stack
* **Language:** Python 3
* **GUI Library:** Pygame
* **Package Manager:** [uv](https://github.com/astral-sh/uv)

## 🚀 Getting Started
This project uses `uv` for dependency management, ensuring a reproducible environment.

### 1. Installation
Ensure you have `uv` installed. If not:
```bash
pip install uv
```

Clone the repository:
```bash
git clone https://github.com/Alireza2317/chess-gui-python
cd chess-gui-python
```

### 2. Run the Game
Sync dependencies and launch:

```bash
uv sync
uv run main.py
```

## 📂 Project Structure
```text
.
├── assets/          # Sprites and images for pieces
├── chess/           # 🧠 Core Engine (Board logic, Move validation, Rules)
├── gui/             # 🎨 Rendering logic (Drawing board, Event handling)
├── main.py          # Entry point
├── pyproject.toml   # Project configuration
└── uv.lock          # Dependency lockfile
```
## Roadmap & Upcoming Features
The following features are currently being developed in experimental branches:
- Move History: Full move recording with persistent storage.
- Undo/Redo System: Implementation of the Command Pattern for game state reversal.
- CLI Mode: A fully text-based terminal version of the game.
- FEN loader and exporter
- and much more ...
