# Java-Less-is-More-Game  
## 🚀 A Mathematics Game written in Java 

Welcome reader, this is a cool project which I have made that has a lot of cool features!  
Numbers on the buttons are set to a random digit between 1 and 9.  
- The **target value** is displayed above the field.  
- The **current sum** of numbers on the buttons is displayed below the field.  
- The **number of moves** until the end of the game is displayed in the top right corner above the field.

---

## 🎯 Game Objective:
The goal of the game is to select buttons on a grid so that the sum of their values gets as close as possible to a given target value.

## 🧩 How It Works:
- When you press a given button, you **cannot press the same button again**.
- The value of the button pressed determines **all the rows divisible by that number**.
- The second time you press a button, the rules **switch**! You can choose all the **intersections** between the rows divisible by the value of the 2nd button and the **columns of the previous value**.

---

## 🛠️ Tasks:
- **Dynamic Field Layout**: The game generates a new field layout for each session, with a default grid size of 10 × 10.
- **Save & Load Field Layout**: Players can save the current game field to a file and load previously saved layouts for future play.
- **Game Control Menu**: A versatile game menu allows players to restart the game, set a custom field size, define the number of moves, and set the target value.
- **Difficulty Settings**: The game offers difficulty options—easy, medium, and hard—that adjust the target value and number of moves.
- **Solution Quality Display**: When the move counter reaches zero, the graphical interface will display the deviation from the target value.
- **Game Continuation Detection**: The game detects when no further moves are possible.

---

Enjoy the challenge, and aim for the perfect sum!

