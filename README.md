# 🎯 Number Guessing Game

## 📌 Project Information

* **Internship:** CodeSoft Java Programming Internship
* **Task:** Task 1 – Number Guessing Game
* **Language:** Java
* **IDE:** VS Code / Eclipse / IntelliJ IDEA
* **Author:** Dhanya Priya

---

## 📖 Project Description

The **Number Guessing Game** is a simple Java console application where the computer randomly generates a number between **1 and 100**. The player has **10 attempts** to guess the correct number.

After each guess, the program provides feedback indicating whether the guessed number is **too high** or **too low**. If the player guesses correctly within the allowed attempts, the score increases by one. At the end of each round, the player can choose to play again.

---

## ✨ Features

* Random number generation between **1 and 100**
* Maximum of **10 attempts** per round
* Feedback for each guess:

  * Too High
  * Too Low
  * Correct Guess
* Score tracking across multiple rounds
* Option to play multiple games
* User-friendly console interface

---

## 🛠 Technologies Used

* Java
* Object-Oriented Programming (OOP)
* `java.util.Random`
* `java.util.Scanner`

---

## 📂 Project Structure

```
NumberGuessingGame/
│── NumberGuessingGame.java
│── README.md
```

---

## ▶️ How to Run

1. Clone the repository.

```bash
git clone https://github.com/your-username/NumberGuessingGame.git
```

2. Navigate to the project folder.

```bash
cd NumberGuessingGame
```

3. Compile the program.

```bash
javac NumberGuessingGame.java
```

4. Run the program.

```bash
java NumberGuessingGame
```

---

## 💻 Sample Output

```
=== Number Guessing Game ===
Guess a number between 1 and 100
You have 10 attempts.

Enter your guess: 50
Too High!

Attempts left: 9

Enter your guess: 25
Too Low!

Attempts left: 8

Enter your guess: 37
Correct! You guessed the number.

Current Score: 1

Do you want to play again? (Y/N):
```

---

## 📚 Concepts Used

* Random Number Generation
* Loops (`for`, `do-while`)
* Conditional Statements (`if-else`)
* User Input
* Variables and Data Types
* Score Management

---

## 🎯 Learning Outcomes

Through this project, I learned how to:

* Generate random numbers in Java
* Take user input using `Scanner`
* Implement looping and conditional logic
* Track scores across multiple rounds
* Build an interactive console-based application

---

## 🚀 Future Enhancements

* Add difficulty levels (Easy, Medium, Hard)
* Allow users to choose the number range
* Maintain a high score leaderboard
* Display statistics such as wins and losses
* Add input validation for invalid entries

---

## 👩‍💻 Author

**Dhanya Priya**

**CodeSoft Java Programming Internship – Task 1**
