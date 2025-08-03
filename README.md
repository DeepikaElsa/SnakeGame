# Snake Game in C (Console-Based)

This is a simple **console-based Snake Game** written in C. The player controls a snake head (`0`) on a 20x20 grid, collecting fruits (`*`) to earn points. The game ends if the snake hits the wall or the user presses `X`.

---

## 🎮 Features

- Console-based gameplay using ASCII characters
- Real-time user input handling
- Random fruit generation
- Scoring system
- Exit the game by pressing `X`

---

## 🖥️ Requirements

To compile and run this game, you'll need:

- A C compiler (e.g., GCC)
- A Windows terminal environment (uses `<conio.h>`, `<unistd.h>`, and `system("cls")`)

> ⚠️ This game is designed for Windows. For Linux or macOS, some parts (like `getch`, `kbhit`, and `system("cls")`) may need replacements or compatibility wrappers.

---

## 📦 Files

- `game.c` — Source code of the Snake game
- `game.exe` — Precompiled Windows executable (if available)

---

## 🛠️ How to Compile

Open a command prompt and compile using GCC:

```bash
gcc game.c -o game.exe
```
## ▶️ How to Run

Once compiled

```bash
./game.exe
```
## 🎮 Controls

| Key | Action     |
| --- | ---------- |
| `W` | Move Up    |
| `S` | Move Down  |
| `A` | Move Left  |
| `D` | Move Right |
| `X` | Exit Game  |

## 📝 Notes
The snake doesn't grow after eating fruit.
There's no body or self-collision logic—just a basic head and fruit interaction.
Game speed is managed using sleep(0.01) which might behave differently on various systems.




