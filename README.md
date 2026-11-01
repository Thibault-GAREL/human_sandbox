# 🏡 Village Simulator

![Python](https://img.shields.io/badge/python-3.9%2B-blue.svg)
![Pygame](https://img.shields.io/badge/Pygame-2.6.1-red.svg)

![License](https://img.shields.io/badge/license-MIT-green.svg)  
![Contributions](https://img.shields.io/badge/contributions-welcome-orange.svg)  

<p align="center">
  <img src="img/Gif-human-sandbox.gif" alt="logo">
</p>

## 📝 Project Description  
🧑‍🌾This project is a **sandbox village life simulator** built with Pygame.  
Villagers wander, eat carrots, reproduce, and grow over time.  

It’s a mix between a **tiny ecosystem** and a **genetic playground**.  
Carrots spawn randomly, villagers collect them to feed babies, and new villagers appear when couples meet.  

The simulation includes visual feedback with particles❤️, trees🌳, and isometric-style rendering🔷.  

---

## 🎮 Example Screenshots  
Here’s a preview of the simulation:  

![Village Example](img/example.png)  

---

## 🗺️ How it works

The simulation works on a **grid-based map** defined by a simple text file (`map.txt`):  

- `#` → solid block  
- `~` → water  
- `T` → tree  
- `.` → grass  

The map is loaded at startup and drawn with depth layering to keep visuals consistent.  

---

## 📂 Repository structure  
```bash
├── img/            # All images used on the code and the README
│
├── map.txt         # We can change the configuration of the map easily : Add Trees, change the forme or the block,...
├── village.py
│
├── LICENSE
├── README.md
```

---

## 💻 Run it on Your PC  
Clone the repository and install dependencies:  
```bash
git clone https://github.com/Thibault-GAREL/human_sandbox.git
cd human_sandbox

python -m venv .venv # if you don't have a virtual environment
source .venv/bin/activate   # Linux / macOS
.venv\Scripts\activate      # Windows

pip install pygame

python main.py
```

---

## 📖 Inspiration / Sources  
The idea is to have a solid base for natural selection for futur project !  😆 100% coded by myself, no tutorials!

I was inspired by the video of [Code BH - J'ai codé une simulation pour comprendre l'égoïsme.](https://www.youtube.com/watch?v=qVOjXQUzOJw)


Code created by me 😎, Thibault GAREL - [Github](https://github.com/Thibault-GAREL)
