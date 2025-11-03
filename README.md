# ⚔️ RannDemo — 2D Action Prototype  

**RannDemo** is a small Unity project created as a prototype for a simple 2D action game.  
It includes basic combat, enemies, traps, checkpoints, and a complete UI system.  
All assets and animations are taken from free open-source sources and used for learning purposes.  

---

## ✨ Features  

### Player  
- Move, jump, and attack with a sword  
- Take and deal damage  
- 1-second invulnerability after being hit  
- Respawn after death or from the latest checkpoint  
- Pick up hearts to restore health  

### Enemies  
- Patrol between two points  
- Detect and attack the player when close  
- Deal melee damage  

### Traps  
- **Saw Traps** — move back and forth, deal contact damage  
- **Arrow Traps** — shoot arrows that damage the player  
- **Fire Traps** — activate 1 second after stepping on them  
- **Spike Traps** — deal damage when stepped on  

Traps are automatically disabled when leaving a room to reduce system load.  

### Checkpoints  
- Save player position  
- Play a sound when activated  
- Respawn the player on death instead of showing the “You Died” screen  

---

## UI System  
- **Health Bar:** heart icons in the top-left corner  
- **Pause Menu:**  
  - Resume  
  - Increase/Decrease music volume  
  - Increase/Decrease sound effects volume  
  - Exit to main menu  
  - Quit game  
- **Death Screen:** restart or return to main menu  
- **Main Menu:** includes “Play” and “Exit” options  

---

## Project Structure  
- **Core** — camera and sound management  
- **Player** — movement, attack, respawn, sword hitbox  
- **Enemies** — patrol and melee AI  
- **Traps** — all trap types and their logic  
- **Health** — player HP and collectible hearts  
- **UI** — menus and health display  

---

## Future Ideas  
- Add a boss fight  
- Add save/load system  
- Improve animation transitions  
- Add simple level selection screen  

---

## 👤 Developer  
Developed by **Rodion**  
🎮 Unity Developer (Learning Project)  
📨 Telegram: [@Rodionbdev](https://t.me/Rodionbdev)  
🆔 Discord: `1255968122754699305`  

