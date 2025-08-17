# Vikings Chess Game

A Java implementation of a **chess-like board game** inspired by Hnefatafl (Vikings Chess).  
The project includes a full game logic engine, a GUI built with **Java Swing**, and unit tests with **JUnit 5**.

---

## 🎮 Game Rules (Simplified)
- You can read the entire rules here https://en.wikipedia.org/wiki/Tafl_games
- The game is played on an **11x11 board**.  
- **Player 1 (Defender)** controls the **King** and 12 Pawns.  
- **Player 2 (Attacker)** controls 24 Pawns.  
- The **goal for Player 1** is to move the King to one of the **four corners**.  
- The **goal for Player 2** is to **capture the King** by surrounding him on all 4 sides.  
- Pawns can capture by flanking enemy pieces horizontally or vertically.  

---

## 🛠️ Features
- Object-oriented design with dedicated classes for:
  - `Board`, `Position`, `Movement`
  - `Piece`, `Pawn`, `King`
  - `Player`, `ConcretePlayer`, `ConcretePiece`
  - `GameLogic` (main engine)
- Graphical interface built with **Swing**:
  - Click-to-move mechanics
  - Highlighting selected pieces
  - Reset & Undo functionality
- Game statistics:
  - Number of moves per piece
  - Number of captures
  - Distance traveled by pieces
  - Most stepped-on squares
- Unit testing with **JUnit** for validating game mechanics.
