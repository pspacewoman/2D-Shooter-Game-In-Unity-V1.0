# 🎮 **2D Shooter Game in UNITY**  

![Unity](https://img.shields.io/badge/Unity-100000?style=for-the-badge&logo=unity&logoColor=white)  

📌 **Live Game (Version 1.0)**: 

[Behance Link](https://www.behance.net/gallery/223175801/2D-Shooter-Game)

https://priyanshi-singh.itch.io/2d-shooter-game-unity-v1

📌 **Live Game (Version 2.0)**: 

[Behance Link](https://www.behance.net/gallery/223257407/2D-Shooter-Game-UNITY-(V20))

https://priyanshi-singh.itch.io/2d-shooter-game-unity-v2


![Platform](https://img.shields.io/badge/Platform-PC%20&%20Web-blue?style=for-the-badge)  
![Status](https://img.shields.io/badge/Status-Completed-green?style=for-the-badge)

![Version](https://img.shields.io/badge/Version-3.0%20Coming%20Soon-orange?style=for-the-badge)

---

🚀 From Game Player to Game Developer. The only thing more fun than playing games is making them. 

---
Built From Scratch👩🏻‍💻 
Added my own notes below for understanding the development process 📝

<img width="300" alt="Thumbnail" src="https://github.com/user-attachments/assets/df2e954d-15af-4d20-b04a-c45353a0ea94" />


## 🚀 My Objective

- Creating 2D Game  
- Working with 2D Sprites  
- Create 2D Animations  
- Implement 2D Mechanics  
- Create a complete game loop  
- Create UI elements that work across multiple resolutions and aspect ratios  
- Build the game for multiple platforms  

<img width="729" alt="Level3-Unity" src="https://github.com/user-attachments/assets/d5ba3fec-a191-4be7-9ecd-43fea7bac8a1" />

---

<details>
<summary>🎮 <strong>UNITY INPUT</strong></summary>

- Input Manager (built-in)  
- Input System (package) --- For this project, I used this input system.  
- 3rd-party Input (ex: rewired)  
</details>

---

<details>
<summary>🧱 <strong>Setting up 2D Game on Unity</strong></summary>

1. **Assets**  
2. **Animation**  
3. **Animator**  
4. **Player Health & Damage Setup**  
   - Physics Interactions: collider, RigidBody component, Custom Script Component  
5. **Player Shooting Setup**: added player effect, shooting component and audio, converted player object to player prefab for iterative use  
6. **Camera Setup**: created 2 camera prefabs - a large camera and a small camera with different sizes  
7. **Level Setup**: created borders, backgrounds and test movement around the space  

</details>

<img width="425" alt="Game Over" src="https://github.com/user-attachments/assets/1bcfddd0-6183-45a5-a873-6bdd11c1553c" />

---

<details>
<summary>🧩 <strong>Game Flow and UI Setup</strong></summary>

### 1. Game Manager and UI Manager Setup  
- Created Game Manager and UI manager  
- Created Canvas and EventSystem  

### 2. UI Setup: Score  
- User Interface (UI): UNITY supports multiple methods for creating UI.  
  + IMGUI  
  + UI Toolkit  
  + Unity UI package (uGUI): using this in my project  
- Created Score and High Score buttons in canvas  

### 3. UI Setup: Pause Screen  
- Created pause and unpause button  
- Added components on it and actions like escape and toggle when it appears during gameplay  

### 4. Responsive and Scalable UI  
- Created new Aspect Screen 4:3  
- Set the 'score' and 'high score' static on the screen and fixed while moving around by: selecting anchor presets  

### 5. UI Setup: Other IN-GAME UI  
- Adding 2 screens: one for when a player loses and one for when a player wins  
- GameOverScreen  
- LevelVictoryScreen  
- Added a 'main menu' button on the pause screen as well  

### 6. UI Setup: Main Menu  
- Setting up the main menu within a new UNITY Scene  
- Assets > _Scenes > MainMenu (scene created)  
- Added all the scenes level1 and mainmenu on Build profiles > all scenes and tested the flow  

### 7. Finish the Gameplay Loop  
- For scene Level1:  
- Added 2 more enemies in the game  
- Changed CANVAS > InGameUI and made it a prefab under UIpages  

### 8. MUSIC  
- Adding 2 music in one main menu and another on the game levels  
- hierarchy > create empty > music name > added component 'audio source' > prefab drag drop music to component > done  


<img width="300" alt="Main Menu" src="https://github.com/user-attachments/assets/022c47b2-511b-4365-939a-1c587f4b0d6c" />    <img width="300" alt="LevelComplete" src="https://github.com/user-attachments/assets/57653c9c-ecb5-491e-9637-1feba6866f73" />




</details>

---

<details>
<summary>🎯 <strong>Fiinal Development Version 1.0</strong></summary>

### 1. Added More Levels  
- Duplicate Scene Level1 to Level2 and Level3 and add them to build profiles  
- Goto Scene Leve1 > NextLevelScreen > set to Level2  
- Same for Level2 > Level3  

### 2. A Deeper Dive Into TextMesh Pro  
- Created new textmesh pro and applied changes like color, wraptext, and other relevant changes required in your text font  

### 3. Code Walkthrough  
- Assets > Scripts  
- Understanding how Unity attributes can be modified by both unity and by visual studio  

### 4. Finished the Project (VERSION 1.0)  
- Build Game Profiles for MaC, Windows, WebGl
- Tested on Web and MacOS - Success
- Uploaded the game on itch.io for view (https://priyanshi-singh.itch.io/2d-shooter-game-unity)

</details>

---

<details>
   
<summary>🧩 <strong>Final Project</strong></summary>

## Checklist:

- [ ] Make **three significant modifications** to the original game.
- [ ] Choose a **new name for the game** and update the **UI to reflect the new title** throughout the game.
- [ ] Ensure there are **no bugs**, **gameplay flaws**, or **look-and-feel issues** before publishing.
- [ ] On **Itch.io**:
  - [ ] For **Windows and Mac builds**, select **"Executable"** and specify the correct platform.
  - [ ] For **WebGL builds**, check **"This file will be played in the browser"**.
  - [ ] Include a description of your **three significant modifications**.
  - [ ] Add **game credits**: *"Created by [Your Name]"*.


</details>

---

<details>
   
<summary>🧩 <strong>Modification In Version 2.0</strong></summary>

### 🎨 Design Modifications
- [ ] Create a complete, interesting, comprehensive, and coherent level.
- [ ] Add multiple additional levels and tie them in to create a logical progression in your game.  
  *(NOTE: Each level should be unique in some way, such as different types of challenges for the player.)*
- [ ] Modify the out-of-game menus in some significant and meaningful way.

### 🖼️ Aesthetic (Visual/Audio) Modifications
- [ ] Reskin the existing graphics in some significant way, such as changing the player or an enemy to a completely different character.
- [ ] Add additional significant and coherent graphical elements to the game, such as new enemies or environmental challenges, complete with animated states.
- [ ] Replace all sound effects in the game to update the sound design.  
  *(NOTE: You must change **all** the sound effects for this to be significant.)*
- [ ] Add custom music to your game.  
  *(NOTE: “Custom” means music you created with a tool like Garage Band or Fruity Loops. Swapping tracks found online doesn't count as significant.)*

### 🎮 Gameplay Modifications
- [ ] Add new player abilities, such as modified controls, additional moves, or additional power-ups.
- [ ] Add new enemies with their own behaviour.  
  *(NOTE: This counts as two modifications if you create unique behavior **and** create the art and animation.)*
- [ ] Add new obstacles and challenges.  
  *(NOTE: This counts as two modifications if you create unique behavior **and** create the art and animation.)*
- [ ] Modify the in-game GUI in a significant way.


</details>


