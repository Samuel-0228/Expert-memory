# 🎮 Number Guessing Game (C++)

A simple console-based number guessing game built in **C++**.  
The program generates a random number between **1 and 1000**, and you try to guess it with hints like “Too large” or “Too small.”  
Your performance is rated based on how many tries it takes to get the correct number.

---

## 🚀 Features
- 🎲 Random number generation using `rand()` and `time(0)`
- 🧠 Smart hints to guide your guesses
- 🔁 Option to play again
- 💬 Feedback based on number of attempts

---

## 🧩 How It Works
1. Run the program.
2. Enter `y` to start the game.
3. Guess numbers until you find the secret one.
4. The game tells you if your guess is **too high** or **too low**.
5. Once you guess correctly, it shows:
   - 👑 *“You're a legend”* if under 10 tries
   - 😅 *“You at least got it”* if exactly 10 tries
   - 🧩 *“Try smart next time”* if over 10 tries
6. You can choose to play again.

---

## 🛠️ How to Run

### Using a C++ Compiler
```bash
g++ -o guess_game main.cpp
./guess_game
