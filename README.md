# 🧺 Falling Object Catcher Game

This is a fun and simple **p5.js + p5.play** arcade game where you catch falling objects using a basket. Earn points by catching them — and don’t let too many fall, or you lose!

---

## 🎮 How to Play

* Use the **left ⬅️** and **right ➡️** arrow keys to move the basket.
* Catch the falling objects (colored circles) to gain points.
* Each catch gives you **+1 point**, missing one costs **-1 point**.
* Reach **15 points to win** or fall to **-5 points to lose**.

---

## 🌟 Features

* Custom background and basket image
* Two randomly colored falling objects with varied speeds
* Real-time collision detection with score tracking
* Game over and win states with messages

---

## 📁 File Structure

```
catcher-game/
├── assets/
│   ├── bg.png           # Background image
│   └── basket.png       # Basket image
├── acript.js            # Main game code
├── README.md            # This file
```

---

## 🛠️ Built With

* [p5.js](https://p5js.org/)
* [p5.play](https://molleindustria.github.io/p5.play/)

---

## 🚀 Getting Started

1. Open the project in the [p5.js Web Editor](https://editor.p5js.org/).
2. Add the `p5.play` library through the **Settings > Libraries** panel.
3. Upload your background and basket images under the `assets` folder.
4. Hit **Play ▶** and start catching!

---

## 🧠 Concepts Learned

* Object movement and keyboard input
* Sprite collision and score handling
* Game state transitions (win/lose)
* Image preloading and background rendering