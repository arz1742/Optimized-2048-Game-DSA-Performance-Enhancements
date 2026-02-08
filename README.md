# 🎮 Optimized 2048 Game – Performance & Gameplay Enhancements

An **enhanced version of the classic 2048 game**, focused on **algorithmic optimization, memory efficiency, and dynamic gameplay mechanics**.  
This project improves upon the traditional 2048 implementation by introducing **optimized tile merging**, **object pooling**, and **progressive difficulty**, resulting in smoother gameplay and higher replay value.

---

## 📌 Project Overview

The 2048 game challenges players to combine numbered tiles on a 4×4 grid to reach the value **2048**.  
While the original game is engaging, it can suffer from performance issues, static difficulty, and inefficient memory usage.

This project addresses those limitations by:
- Reducing time complexity in tile movement & merging
- Optimizing memory usage using object pooling
- Introducing adaptive difficulty based on player performance

---

## ✨ Novel Features & Improvements

### ⚡ Optimized Tile Merging
- Reduced worst-case time complexity from **O(n²) → O(n)**
- Streamlined movement and merge logic for faster execution
- Improved responsiveness during late-game scenarios

### 🧠 Progressive Difficulty System
- Difficulty dynamically adjusts based on player score
- Higher scores introduce:
  - Increased tile spawn frequency
  - Higher-value tiles
- Keeps gameplay challenging and engaging over time

### 🧺 Object Pooling (Memory Optimization)
- Tiles are reused instead of frequently instantiated/destroyed
- Significantly reduces garbage collection overhead
- Ensures smoother frame rates during long play sessions

---

## 🧱 Core Architecture

- **GameManager** – Controls game state, score, and game lifecycle  
- **TileBoard** – Handles tile movement, merging logic, and game rules  
- **Tile** – Represents individual numbered tiles  
- **TileGrid / TileCell** – Manages grid structure and positioning  
- **TileState** – Defines tile properties (value, color, appearance)

---

## 🧠 Algorithms Used

- Tile Movement Algorithm  
- Tile Merge Algorithm  
- Game Over Detection Algorithm  
- Progressive Difficulty Algorithm  
- Object Pooling Algorithm  

---

## 🛠️ Technologies Used

- **Game Engine:** Unity  
- **Language:** C#  
- **IDE:** Unity Editor  

---

## ▶️ How to Run

1. Install **Unity (2020.3.x or compatible)**
2. Open the project in Unity Hub
3. Load the main scene
4. Click ▶️ Play

---

## 📊 Results & Outcomes

- Reduced lag during tile movements
- Improved memory usage with fewer runtime allocations
- Increased replayability due to adaptive difficulty
- Cleaner and more maintainable codebase

---

## 🎯 Learning Outcomes

- Application of Data Structures & Algorithms in games
- Performance optimization techniques
- Memory management using object pooling
- Designing adaptive game mechanics

---
## 📚 References
- Original 2048 implementation inspiration: https://youtu.be/4NFZwPhqeRs
---
## 👨‍💻 Author

**Arzaan Mulla**<br>
**Swapnil Pal**
