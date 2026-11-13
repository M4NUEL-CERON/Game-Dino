# 🦖 Dino Runner

A clone of Chrome's offline dinosaur game, built from scratch with **plain HTML, CSS and JavaScript**: no frameworks, no libraries.

It was one of my first projects while learning to code. I came back to it to clean it up, fix bugs and make it playable on the web.

![Screenshot](screenshot.png)

## 🎮 Play

👉 **[Play it live](https://m4nuel-ceron.github.io/Game-Dino/)**

### Controls

- **Desktop:** press `SPACE` (or click) to jump.
- **Mobile:** tap the screen to jump.
- After a game over, press `SPACE` or tap again to restart.

## ✨ Features

- Running animation with sprites.
- Randomly spawned cacti (obstacles) and background clouds.
- Collision detection with tuned hitbox margins, so it feels fair.
- Progressive difficulty: speed increases at 5, 10 and 20 points, and the sky shifts from noon to afternoon to night.
- Live score counter and instant restart without reloading.
- Touch support for mobile.

## 🛠️ Tech

- HTML5
- CSS3 (`@keyframes` animations, sprites with `background-position`)
- JavaScript (vanilla, zero dependencies)

## 🚀 Run locally

No install needed, but serve the folder: the game loads images, and opening `index.html` directly (`file://`) can be blocked by the browser.

```bash
git clone https://github.com/M4NUEL-CERON/Game-Dino.git
cd Game-Dino
python3 -m http.server 8080
```

Then open [http://localhost:8080](http://localhost:8080).

## 📁 Project structure

```
Game-Dino/
├── index.html          # Page markup
├── css/
│   └── style.css       # Styles and animations
├── js/
│   └── main.js         # Game loop, physics, collisions, score
├── assets/
│   └── img/
│       ├── dino.png    # Dinosaur sprite
│       ├── cactus1.png # Obstacle sprite (small cactus)
│       ├── cactus2.png # Obstacle sprite (large cactus)
│       ├── nube.png    # Cloud sprite
│       └── suelo.png   # Ground sprite
└── screenshot.png      # Screenshot used in this README
```

## 🙋 Author

**Manuel Cerón** · [Portfolio](https://manuelceron.vercel.app) · [@M4NUEL-CERON](https://github.com/M4NUEL-CERON)

## 📄 License

[MIT](LICENSE)
