# TerranShowcase
This is a showcase of my Unity skills in the form of a multiplayer, procedurally generated, roguelike. NPCs use A* pathfinding to follow their targets. The pathfinding is optimized by utilizing Unity's burst compiler for enhanced speed and space utilization. Over 5000 npcs can actively pathfind while still maintaining a framerate of above 60fps. The map can be dynamically editted by clicking on spaces to remove/add walls. Versioned cachemaps are used to allow pathfinding NPCs to react to changing environments. NPCs can be clicked to "confuse" them, causing their movement to become pseudo-random. All chunks are generated at runtime, and are saved to the disk. Due to this, the map size is effectively infinite, but distortions may appear at very very far distances due to floating point percision errors.

I created this project to explore how roguelike systems could be modernized by including realtime movement and multiplayer features. I still work on this project in my free time and hope to release it as a full game sometime in the future. I intend to add combat mechanics, rpg systems, a system for prefab placement on the map, tools for prefab creation, and more robust systems for NPC AI.

A playable version of the game demo can be found [HERE](https://github.com/jonasenglish/TerranShowcase/releases/tag/Release)

<img width="953" height="758" alt="image" src="https://github.com/user-attachments/assets/cbca2ad2-8113-4e9e-af10-6b0f28c1aada" />
<img width="953" height="758" alt="image" src="https://github.com/user-attachments/assets/cbca2ad2-8113-4e9e-af10-6b0f28c1aada" />
