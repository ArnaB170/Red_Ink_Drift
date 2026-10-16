# RED INK DRIFT — Runaway Grading Pen Arcade ✒️

> You are a runaway, rocket-powered red grading pen on an endless exam sheet. Circle terrible student answers to grade them and dissolve your lethal ink trail!

![Red Ink Drift](https://img.shields.io/badge/Game-Arcade%20Survival-red?style=for-the-badge)
![HTML5 Canvas](https://img.shields.io/badge/Tech-HTML5%20Canvas%20%2B%20Web%20Audio-orange?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)

---

## 🎮 Play Online

👉 **[Play Red Ink Drift in Your Browser!](https://arnab170.github.io/Red_Ink_Drift/)**

No installation or download required — works directly on Desktop, Mobile, and Tablet browsers.

---

### Run Locally

```bash
# Clone the repository
git clone https://github.com/ArnaB170/Red_Ink_Drift.git

# Navigate into the folder
cd Red_Ink_Drift

# Open index.html in your default browser
# Windows:
start index.html
# macOS:
open index.html
# Linux:
xdg-open index.html
```

---

## 📜 How to Play

### 1. Circle & Grade Bad Answers
- Your pen leaves a **lethal red ink trail**.
- Steer around ungraded student answers (e.g. `"2 + 2 = 5"`, `"x = vibes"`, `"Proof: trust me bro"`) and close the loop.
- Closing a loop around an answer dissolves that ink loop, stamps a red grade (like `F-`, `0/10`, `SEE ME!`), and increments your combo score multiplier!

### 2. Avoid Self-Collisions & Traps
- **Self-Collision**: Crossing your own wet red ink trail *without* enclosing an answer causes an instant crash!
- **Pink Pearl Erasers**: Patrolling giant erasers wipe ink trails and erase you if you crash into them. Watch for their telegraphed turn arrows.
- **White-Out Puddles**: Running over correction fluid temporarily locks your steering straight ahead for 1.0 second.

### 3. 60-Second Coffee Spill Boss
- Every 60 seconds, an espresso mug tips over!
- Watch the warning perimeter and steer your pen to the designated safe zone before the flood wave hits the sheet.

---

## 🕹️ Controls

| Action | Keyboard | Touch / Mobile |
| :--- | :--- | :--- |
| **Steer Left** | `A` or `Left Arrow` | Left Touch Button |
| **Steer Right** | `D` or `Right Arrow` | Right Touch Button |
| **Rocket Boost** | `Spacebar` | Boost Touch Button |
| **Pause / Resume** | `Esc` or `P` | Pause Button (HUD) |
| **Restart Game** | `R` | Restart Button |
| **Toggle Sound** | `M` | Mute Button (HUD / Menu) |

---

## ✨ Features

- **Procedural Notebook Paper**: Realistic paper grain, ruled lines, red margins, ring-binder holes, and permanent graded markings.
- **Web Audio API Engine**: Pure procedural audio synthesized entirely in the browser (marker squeaks, rubber stamp thuds, rocket hums, chime arpeggios, splatter effects).
- **Zero Build Dependencies**: Written entirely in vanilla JavaScript with HTML5 Canvas and Tailwind CSS via CDN.
- **Touch & Mobile Support**: Responsive controls for smartphones and tablets.

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
