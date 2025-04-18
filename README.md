# Snake Game

Two versions of the classic Snake game:

1. **C Console Version** (`snake game.c`)
2. **Browser Version** (`snake game.html` for Desktop and `snake-mobile.html` for Mobile)

# To play The Game
1. **C program file (exe)**: [Download Snake Game.exe](/snake_game/snake%20game.exe)
2. **Play on Mobile**: [Play On Phone](/snake_game/snake-mobile.html)
3. **Play on Desktop Browser**: [Play on Desktop](/snake_game/snake%20game.html)
4. **Modify The C Code**: [Download & Modify Code](/snake_game/snake%20game.c)


---

## 📂 Folder Structure

your-repo/ ├── snake.c ├── snake.html ├── README.md ├── LICENSE └── .gitignore

yaml
Copy
Edit

---

## 🐍 C Console Version

### Prerequisites

- **Windows**
- **MinGW** (GCC) or **Visual Studio**

### Build & Run with MinGW

gcc snake.c -o snake.exe
./snake.exe
Or open a new Console‑App project in Visual Studio, add snake.c, then build & run.

🌐 Browser Version
Prerequisites
Any modern web browser

(Optional) Python 3 for a local HTTP server

Play Directly
Double‑click snake.html in your file explorer.

The game canvas appears; press W A S D or the arrow keys to start moving.

When the game ends, your final score shows below and a green Restart button appears.

Play via Local HTTP Server
Avoids any “blocked” scripts if your browser is strict.

Open a terminal in this folder.

Run:

bash
Copy
Edit
python3 -m http.server 8000
In your browser go to:
http://localhost:8000/snake.html

### 🎮 How to Play
Move: W (up), A (left), S (down), D (right)

Eat the red square (fruit) to grow and earn +10 points

Avoid hitting walls or your own tail

Game Over: your score appears below the canvas

Restart: click the green Restart button
```
