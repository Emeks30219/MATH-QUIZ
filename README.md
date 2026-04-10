# ➗ Math Quiz Game

A command-line math quiz game built with Python. The game generates random arithmetic problems and challenges you to solve them as fast as possible — tracking your time and wrong answers along the way.

---

## 📋 Features

- Randomly generates addition, subtraction, and multiplication problems
- Tracks total time taken to complete all problems
- Keeps retrying the same problem until you get it right
- Counts wrong answers
- Simple, clean terminal interface

---

## 🛠️ Built With

- Python 3
- `random` module (built-in)
- `time` module (built-in)

No external libraries needed.

---

## 🚀 How to Run

1. Make sure Python 3 is installed on your machine.
2. Clone or download this repository.
3. Open a terminal in the project folder.
4. Run the script:

```bash
python math_quiz.py
```

5. Press **Enter** to start, then type your answers when prompted.

---

## 🎮 How to Play

- You will be given **10 math problems** one at a time.
- Type your answer and press **Enter**.
- If your answer is **wrong**, the same problem will repeat until you get it right.
- After all 10 problems, your **total time** is displayed.

**Example:**

```
PRESS ENTER TO START!
-----------------------
problem #1: 7 + 9 = 16
problem #2: 5 * 8 = 40
...
-----------------------
Nice work! You finished in 34.57 seconds!
```

---

## ⚙️ Configuration

You can customize the game by editing these constants at the top of the file:

| Constant        | Default | Description                        |
|-----------------|---------|------------------------------------|
| `TOTAL_PROBLEMS` | `10`   | Number of questions per game       |
| `MIN_OPERAND`   | `3`     | Smallest number used in problems   |
| `MAX_OPERAND`   | `12`    | Largest number used in problems    |
| `OPERATORS`     | `+`, `-`, `*` | Math operations included   |

