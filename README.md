# 🕹️ 2D Platformer Project (PRO 1)

![PJATK](https://img.shields.io/badge/University-PJATK_Warsaw-red)
![Course](https://img.shields.io/badge/Course-PRO_1-green)
![Unity](https://img.shields.io/badge/Made_with-Unity-black?logo=unity)
![C#](https://img.shields.io/badge/Language-C%23-blue)

**[Black Horizon]** is a 2D platformer game created as a final project for the **PRO 1** (Programming 1) course at the **Polish-Japanese Academy of Information Technology (PJATK)** in Warsaw, Department **XRG**. 

## 🎥 Gameplay Showcase

[![Game Gameplay](https://img.youtube.com/vi/TWOJ_LINK_DO_YOUTUBE/hqdefault.jpg)](https://www.youtube.com/watch?v=TWOJ_LINK_DO_YOUTUBE)<br>
*(Click the image above to watch the gameplay video on YouTube)*

## 💡 About the Project

This project is a feature-rich 2D platformer built entirely from scratch in **Unity** using **C#**. It was developed by a team of 4 students to demonstrate proficiency in game logic, physics, UI/UX, and system architecture.

The game offers a dynamic platforming experience with a variety of movement mechanics, combat encounters, and environmental puzzles. 

### ✨ Key Features & Mechanics:
* **Combat System:** Both melee and ranged attack mechanics for the player.
* **Enemy AI:** Programmed AI behaviors for both melee and ranged enemies, offering diverse combat challenges.
* **Advanced Movement:** Fluid character controller featuring abilities like **double jump** and **dash**.
* **Dynamic Environments:** Levels built using Unity's **Tilemap** system, featuring interactive elements like trampolines, moving platforms, and disappearing platforms.
* **Game Systems:**
  * A robust **Save System** to keep track of player progress.
  * Comprehensive and polished **UI / GUI** menus.
  * A custom **Dialogue System** for storytelling and NPC interactions.
* **Collectibles:** Various hidden items to collect throughout the levels.
* **Visuals:** Custom 2D animations that bring the characters and the world to life.

## 🛠️ Technologies & Tools

* **Game Engine:** Unity 2022.3.46f1 (LTS), 2D
* **Programming Language:** C#
* **Level Design:** Unity Tilemap System
* **UI/UX:** Unity UI

## 👥 Development Team

This project was brought to life by an amazing 4-person team from the XRG department:

* **[Dawid Juszyński (VeeturN)](https://github.com/VeeturN)** - Developer 
* **[Olaf Mickiewicz (Nick 2)](https://github.com/link_do_githuba)** - Developer
* **[Jędrzej Nowakowski (End0m0nd0)](https://github.com/End0m0nd0)** - Developer
* **[Aleks Winiarczuk (Nick 4)](https://github.com/link_do_githuba)** - Developer

## 🎓 Credits
A special thanks to the **Polsko-Japońska Akademia Technik Komputerowych (PJATK)** in Warsaw, specifically the **XRG Department**, for providing the knowledge and environment to build this project as part of the PRO 1 course curriculum.

## 🚀 How to Run the Project

### Requirements
* [Git](https://git-scm.com/downloads)
* [Unity Hub](https://unity.com/download)
* **Unity 2022.3.46f1 (LTS)** – the editor version this project was made with. Other 2022.3.x LTS versions should also work.

### Steps
1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/End0m0nd0/Black-Horizon.git
   ```
2. Open **Unity Hub**, go to **Projects → Add → Add project from disk** and select the cloned `Black-Horizon` folder.
3. If Unity 2022.3.46f1 is not installed, Unity Hub will offer to install it – accept, or pick another 2022.3.x version you already have.
4. Open the project. The first launch can take a few minutes while Unity imports assets and generates the `Library` folder.
5. In the **Project** window open the scene `Assets/Scenes/MainMenu.unity`.
6. Press **▶ Play** in the editor to start the game from the main menu.

### Building a standalone version
1. Go to **File → Build Settings…**
2. Make sure `MainMenu` is the first scene in the *Scenes In Build* list.
3. Pick your target platform (e.g. *Windows, Mac, Linux*) and click **Build**.

## 🎮 Controls

| Action | Key |
| --- | --- |
| Move | `A` / `D` or `←` / `→` |
| Jump / Double jump | `Space` |
| Dash (in the air) | `Left Shift` |
| Melee attack | `Left Mouse Button` |
| Ranged attack | `Right Mouse Button` |
| Use inventory item | `1` – `4` |
| Interact | `E` |
| Pause menu | `Esc` |
