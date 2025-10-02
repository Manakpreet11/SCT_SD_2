# 🎲 Number Guessing Game (Java)

A simple console-based **Number Guessing Game** built in Java.
The computer randomly selects a number between **1 and 100**, and the player must guess it.
The program provides feedback (`Too low`, `Too high`) until the correct number is guessed.

---

## 📌 Features

* Random number generation between 1 and 100
* User input handling with **Scanner**
* Feedback on guesses:

  * `Too low! Try again.`
  * `Too high! Try again.`
  * `Congratulations!` message when guessed correctly
* Tracks the **number of attempts** taken to guess the number

---

## 🛠️ Technologies Used

* **Java (JDK 8 or later)**
* **Random class** for number generation
* **Scanner class** for input

---

## 🚀 How to Run the Program

1. **Clone the repository** (if uploaded on GitHub):

   ```bash
   git clone https://github.com/Manakpreet11/number-guessing-game.git
   cd number-guessing-game
   ```

2. **Compile the program**:

   ```bash
   javac NumberGuessingGame.java
   ```

3. **Run the program**:

   ```bash
   java NumberGuessingGame
   ```

---

## 🖥️ Example Output

```
Welcome to the Number Guessing Game!
I have selected a number between 1 and 100.
Can you guess it?
Enter your guess: 50
Too low! Try again.
Enter your guess: 75
Too high! Try again.
Enter your guess: 63
🎉 Congratulations! You guessed the number in 3 attempts.
```

---

## 📂 Project Structure

```
NumberGuessingGame/
│── NumberGuessingGame.java   # Main source file
│── README.md                 # Documentation
```

---

## 📖 Concepts Covered

* **Random number generation** using `Random` class
* **User input handling** using `Scanner`
* **Loops and conditionals** (`while`, `if-else`)
* **Basic game logic and interaction**

---

## 🎯 Possible Enhancements

* Add difficulty levels (Easy, Medium, Hard)
* Limit maximum attempts
* Display a "Game Over" message if attempts run out
* Replay option without restarting the program

---

## 👨‍💻 Author

* **Your Name**
* GitHub: (https://github.com/Manakpreet11)
* Project created during learning Java basics 🚀

---
