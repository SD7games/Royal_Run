# 🏃‍♂️ Royal Run  
A small hyper-casual endless runner made in Unity.  
The player runs through an infinite corridor filled with obstacles, falling objects and collectibles.  
Simple, fast gameplay loop designed for practice and experimentation.

---

## 🎮 Gameplay Overview  
The player automatically moves forward through a procedurally generated corridor.  
The goal is to survive as long as possible while collecting items to keep the timer alive and increase score.

### Core Mechanics  
- **Endless Movement:** continuous forward motion with infinite level generation.  
- **Obstacles:** barrels, chairs, rocks, carts and other objects that block or slow the player.  
- **Falling Objects:** random fun hazards for reaction-based dodging.  
- **Collectibles:**  
  - **Apples** – increase speed and refill time.  
  - **Coins** – collected for score.  
- **Timer System:** time decreases constantly but can be restored by apples and checkpoints, allowing infinite play.  
- **Player Reactions:**  
  - run animation  
  - stumble animation when hitting obstacles (no damage, only visual feedback)  
- **Camera Shake & VFX:** shake on impact, particles when speeding up.  
- **Audio & UI:** footstep sounds, collision effects, pickup sounds, and a minimal HUD.  
- **Post-processing:** color grading, bloom, subtle motion polish.

---

## 🧠 Tech & Structure  
- Unity  
- C#  
- Procedural environment generation  
- Simple object pooling  
- Animator-based character reactions  
- Trigger-based collectibles  
- Timer and score logic  
- Lightweight post-processing

---

## 📂 Project Structure
```
/Assets
    /Animations
    /Audio
    /Prefabs
    /Scripts
        /Player
        /Environment
        /Obstacles
        /Collectibles
        /UI
    /Materials
    /Scenes
```

📸 Screenshots
🏃‍♂️ Running & Obstacles
<p align="center"><img src="FunObjects.png" width="420"/></p>
🍎 Collecting Apples (Speed Boost)
<p align="center"><img src="StartLevel.png" width="420"/></p>
🟢 Start Screen
<p align="center"><img src="StartScene.png" width="420"/></p>

---

## 👨‍💻 Developer  
**Oleksandr Tokarev** — Unity & C# Game Developer based in Finland.  
A small practice project made to explore endless-runner mechanics and procedural environment setups.

