# 🐢 Turtle Crossing Game

A beginner-friendly arcade game built with Python Turtle graphics.  
The goal is simple: **move your turtle to the top of the screen without getting hit by cars**!

![gameplay](https://user-images.githubusercontent.com/your-image-link-here.gif)

---

## 🎮 How to Play

- Press the **Up Arrow** to move your turtle forward.
- Avoid the cars coming from the right.
- Every time you reach the top safely, you **level up** and cars get faster!
- If a car hits you — **Game Over**.

---

## 🧠 Key Concepts Used

- Object-Oriented Programming (OOP)
- Python's `turtle` module for GUI/graphics
- Key event listeners (`onkey`)
- Collision detection
- Game loop logic with `time.sleep()` and `screen.update()`

---

## 📁 Project Structure

```text
📦 turtle-crossing-game
├── main.py              # Game loop and core logic
├── player.py            # Turtle player class
├── car_manager.py       # Manages car creation and movement
├── scoreboard.py        # Level display and Game Over message
└── README.md            # This file!
