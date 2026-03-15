# Catch The Diamond 🎮💎
![Language](https://img.shields.io/badge/Language-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Graphics](https://img.shields.io/badge/Graphics-OpenGL-5586A4?style=flat-square)
![Library](https://img.shields.io/badge/Library-PyOpenGL-orange?style=flat-square)
![Toolkit](https://img.shields.io/badge/Toolkit-GLUT-red?style=flat-square)
![Game](https://img.shields.io/badge/Game-2D%20Arcade-green?style=flat-square)
![Project](https://img.shields.io/badge/Project-Computer%20Graphics-purple?style=flat-square)

A simple 2D arcade-style game built using **Python** and **OpenGL**, where the player controls a catcher to collect falling diamonds. The goal is to catch the diamonds before they reach the bottom of the screen.
---

## 📌 Project Overview

**Catch The Diamond** is a beginner-friendly 2D game project that demonstrates:
- Basic game development concepts
- OpenGL rendering
- Keyboard interaction
- Collision detection

This project is suitable for students learning **Computer Graphics** or **Python-based game development**.

a .pyc file is here for preview

---

## ⚙️ Features

- 💎 Falling diamond animation  
- 🎮 Player-controlled catcher  
- ⌨️ Keyboard-based movement  
- 📊 Score tracking  
- ❌ Game over when diamond is missed  

---

## 🛠️ Technologies Used

- **Python 3**
- **OpenGL (PyOpenGL)**
- **GLUT (OpenGL Utility Toolkit)**

---

## 📂 Project Structure

Catch-The-Diamond
│
├── Hello_OpenGL.py
├── lets_draw_sth.py
├── 2Dgame.py
├── README.md
└── OpenGL/ (unzipped OpenGL folder)


⚠️ **Important:**  
You must **unzip the OpenGL folder** and keep it in the **same directory** as all the `.py` files.  
Otherwise, the game will not run.

---

## 🔧 Setup & Installation

### 1️⃣ Install Python
1. Make sure Python 3 is installed.

Check version:
```bash
python --version
```
2. Install Required Libraries

If OpenGL is not installed, run:
```bash
pip install PyOpenGL PyOpenGL_accelerate
```
3. OpenGL Folder Setup (IMPORTANT)

Download the provided OpenGL zip file

Unzip the OpenGL folder

Place the OpenGL folder inside the project directory

Keep all .py files and the OpenGL folder in the same folder

4. How to Run the Game

Open terminal in the project folder

Run the following command:  python 2Dgame.py

🎮 Game Controls

1. Left Arrow (←) → Move catcher left

2. Right Arrow (→) → Move catcher right

3. ESC → Exit the game

🔄 Game Process / Working Logic

The OpenGL window is initialized

1. A diamond falls from the top at a random position

2. The player moves the catcher using arrow keys

3. If the catcher catches the diamond: Score increases, Diamond resets to the top

4. If the diamond reaches the bottom: Game Over


👩‍💻 Author

Ummay Maimona Chaman
GitHub: https://github.com/UmmayMaimonaChaman

📜 License

This project is created for educational purposes only.


✨ Enjoy playing Catch The Diamond!
