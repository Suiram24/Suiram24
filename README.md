### Hi there, I'm Marius 👋

  * 💼 I am a software engineer currently working at Shine Group in the console porting team.
  * 📘 I'm a gratuated engineer from UTBM & UQAC
  * 🌱 Currently working on game engines 
  * 💡 Interested in Games Engines, Game Design, Software architecture and physics simulations.
  * 📫 You can reach me at contact@mbozane.fr

## Shipped and Announced games:

### Terrinoth®: Heroes of Descent
Release announced for spring 2026, [you can check the steam page here](https://store.steampowered.com/app/3929630).

I am currently working on having this Unity game shipped on PS5 and XBox Series. Most of my work here can be summed up with:
- Implementing console-compliant multiplayer features with a P2P that doesn't requires the editor to pay (Unity Relays does not do this).
- Profiling and Optimizing CPU performance. 
- Write test plans and overseeing external QA testing regarding console compliance.

### Rooftops and Alleys: The Parkour Game
Released on consoles in June 2025, [you can check the steam page here](https://store.steampowered.com/app/2703850).

This parkour game was originally solo-developped by Michel Losch on PC, then ported and edited by Shine group and Radical Theory on consoles.

I worked on this project for the entire time it was ported prior to release in june 2025 (aprox. 7/8 months) and then during 3/4 months for post-release updates.
During this time, I had to make sure the game will be console compliant, and implement the multiplayer functionallities in UE 5.4 for Playstation 5, Xbox Series and Nintendo Switch.

An important part of my work was to design and implement the multiplayer module of our porting technology TRX in a way that it is easy to maintain and improve in future games, while keeping it "plug and play".
Even if the Online Subsystems of UE 5.4 does a big part of the job, there are still a lot of things to fix to make them console-compliant and easy to use for blueprint users, as Rooftops is a full BP game.



## Main personal projects:

### Pepper Engine
https://github.com/Suiram24/PepperEngine

This game engine has been started from scratch in an engine physics course, and as been improved past the initial objective.
The initial project was done in a group of 3. I made the architecture, project management and the debug/review of most of the code, and a bit of implementation.

Since then, I made a branche where I implemented Flecs to help me understand how a real ECS work (and not just EC-Framework like the one I made in the initial project).
I then implemented my own ECS, and started to use the engine in game jams.
Because of my job and music activities, I have currently less time to spend on this project, but still come back to it ocasionally.

Things I made in the initial group project:
 * Software architecture of all the engine
 * Project management (division of tasks, deadlines...)
 * Project setup (CMake configuration of the project, management of externals libs)
 * Entity-Component framework implementation (everything that is in the EngineCore lib, and most of the components classes)
 * Implementaton of collision resolution
 * Code review of most of the code
 * Lot of debug in the math and physics parts

Things I made later:
 * Flecs Implementation
 * Custom ECS implementation
   
Things I am doing/planning to do when I have the time:
 * Clean and publish my last jam game using the engine
 * Vulkan textures fixes
 * Queries auto-updating in the ECS
 * Job system
 * Physics - ECS branches Merge
 * CMake cleaning

### Life-VaiR
https://github.com/LifeVair/Life-VaiR

In this serious games in Virtual Reality, I was was working with another student under the supervision of a dev lead as part of a project course at UTBM. 
I made the implementation of one puzzle, including one gameplay mechanic.
This was my first Unreal Engine project, and my first completed VR prototype.

### Other
Other projects I have yet to describe :

* Gang de Croquette: a game made for the Ubisoft University Competition in a group of 8, that has been nominated 4 times. [Try it on for free on steam!](https://store.steampowered.com/app/2988130)
* Elementalist Brush: A VR POC game, in a group of 3, where we implemented a symbol recognition algorithm from scratch and made it work inside an oculus Quest 2.
* Project HC: A little soulslike game made in a game conception course.
* Network : A short network course assignement, in a group of 8, where we replaced the Unreal Engine replication system by our own replication. I worked on the system that serialize the world state of the server and deserialize it in the client.


