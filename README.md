# Crystal Shards — A Browser RPG Adventure

> A retro pixel RPG where you explore villages, collect crystal shards, and defeat shadows to save the kingdom.

---

## 🎮 Play

Open `index.html` in any modern browser. No installs, no dependencies, no build step required.

---

## 📖 Story

The Crystal of Maki has been stolen and shattered into **3 shards** by mysterious shadows. You play as **Lia**, a young hero who must recover the shards from the village, venture into the dungeon, and restore the crystal at the sacred altar before darkness takes over the kingdom.

---

## 🕹️ How to Play

### Controls

| Action | Keyboard | Mobile |
|---|---|---|
| Move | Arrow Keys or W A S D | D-Pad buttons |
| Talk / Attack / Collect | SPACE | ACTION button |
| Skip dialogue | Click text box | SKIP TEXT button |

### Walkthrough

1. **Overworld** — Walk up to the Old Man and press SPACE to hear his warning
2. **Enter the Village** — Walk up through the gate
3. **Collect 3 Shards** — Talk to the Farmer, the Witch, and the Kid; also pick up the glowing shard on the ground
4. **Enter the Dungeon** — Once you have all 3 shards, walk up through the red gate
5. **Defeat the Shadows** — Press SPACE next to each purple shadow to hit it (3 hits each)
6. **Restore the Crystal** — Walk to the golden Altar and press SPACE to win

> ⚠️ If you run out of HP in the dungeon, you'll be sent back to the village and enemies will reset.

---

## ✨ Features

- 3 explorable scenes — Overworld, Village, Dungeon
- NPC dialogue system with callbacks and story progression
- Particle burst effects on shard collection and combat
- Enemy AI with patrol movement
- HP and damage system with invincibility frames
- Step-by-step guidance bar so players always know what to do
- Fully responsive — scales to any screen size
- Touch D-pad controls for mobile play
- Zero dependencies — pure vanilla HTML5 Canvas

---

## 🛠️ Built With

| Technology | Usage |
|---|---|
| HTML5 | Structure |
| CSS3 | Layout & responsive scaling |
| JavaScript (ES6+) | Game logic, state management |
| Canvas 2D API | All rendering & animation |
| requestAnimationFrame | Game loop |
| Touch & Keyboard Event APIs | Input handling |
| Google Fonts — Press Start 2P | Retro pixel typography |

---

## 📁 Project Structure

```
crystal-shards/
├── index.html      # Entire game — single self-contained file
└── README.md
```

---

## 🚀 Getting Started

```bash
# Clone the repo
git clone https://github.com/your-username/crystal-shards.git

# Open the game
open index.html
```

Or simply drag `index.html` into your browser.

---

## 🔮 What's Next

- [ ] Larger overworld with more zones to explore
- [ ] Additional enemy types with unique attack patterns
- [ ] Inventory and equipment system
- [ ] Save/load progress via localStorage
- [ ] Chiptune background music and sound effects
- [ ] Boss fight before the final altar sequence
- [ ] Multiple endings based on play style

---

## 🏆 Accomplishments

- Complete game loop (start → middle → end) in a single vanilla JS file
- Smooth particle system for visual feedback
- Fully responsive layout that works on desktop and mobile
- Dialogue system with chained story callbacks
- Built with zero external libraries or frameworks

---

## 📄 License

MIT — free to use, modify, and distribute.

---

*Made with ♥ and pure JavaScript*