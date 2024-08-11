# Game Design Document: 3D First-Person Roguelite

## 1. Game Overview
### 1.1 Concept
A 3D first-person roguelite game inspired by Lethal Company, featuring a village hub, explorable levels, and challenging dungeons.
The gameplay loop is inspired by lethal company in that there will be 3 basic stages, 1 the village, 2 level, 3 the dungeon. The village will act as a hub for the player, having upgradeable buildings such as a blacksmith and an apothacary for potions, there will also be a plot for a player owned house which they can customise using rewards earned through the game. Progress on the village is continuous with permanent upgrades, hence the game is a rogue lite. The level will be accessed from a carriage in the village, this carriage will be present in the level and will act as a storage space for loot from the dungeon and also hold your weapons and armour you bring over from the village. Take for example one level would be a forest, and when the player arrives in this forest they will have to find the dungeon which could be a cave. When the player goes into this dungeon they will be faced with enemies like skeletons, wolves, spiders, or goblins that will guard treasure hidden throughout the dungeon. The dungeon may also contain various traps. The player must find the treasure and take it back to the carriage outside of the dungeon on the level area whilst avoiding being attacked. If a player dies inside the dungeon or in the level area they will lose all of their items permanently and all loot on the carriage. If however the player manages to get back to the carriage safely with loot they can ask the carriage driver to take them back to the village, where they can sell the loot to buy more upgrades.

### 1.2 Genre
3D First-Person Roguelite

### 1.3 Target Platform
PC (Unity Engine, C#)

### 1.4 Target Audience
Fans of co-op action games, rogue likes, medieval fantasy, and first person action games.

## 2. Gameplay
### 2.1 Core Loop
1. Village (Hub)
2. Level Exploration
3. Dungeon Crawling
4. Day-Night difficulty scaling
5. Returning to village to sell loot and upgrade

### 2.2 Village (Hub)
- Upgradeable buildings (e.g., Blacksmith, Apothecary)
- Player-owned house with customization options
- Permanent upgrades and progress
- Purchase armour, weapons, and upgrades to place on the carriage to take into the level

### 2.3 Level Exploration
- Accessed via carriage from the village
- Carriage serves as storage and equipment holder
- Various level types (e.g., forest)
- Objective: Find the dungeon entrance
- Enemies can spawn here at night

### 2.4 Dungeon Crawling
- Combat with enemies
- Avoiding traps
- Collecting treasure
- Returning loot to the carriage

### 2.5 Death Mechanics
- Player loses all items and loot upon death
- Return to village empty-handed

## 3. Game Elements
### 3.1 Enemy Types
[To be expanded]

### 3.2 Weapons
[To be expanded]

### 3.3 Potions
[To be expanded]

### 3.4 Spells
[To be expanded]

### 3.5 Power-ups
[To be expanded]

### 3.6 Level Types
[To be expanded]

### 3.7 Areas
[To be expanded]

## 4. Technical Specifications
### 4.1 Development Environment

- Game Engine: Unity (Latest stable version)
- Programming Language: C#
- 3D Modeling and Animation: Blender
- Version Control: Git and GitHub
- IDE: Visual Studio Code with Unity integration

### 4.2 Unity Engine Features

- Unity's Universal Render Pipeline (URP) for optimized graphics performance
- Unity's Input System for flexible input handling across different devices
- Unity's NavMesh for AI pathfinding in procedurally generated levels
- Cinemachine for advanced camera control and first-person perspective
- Unity's Particle System for visual effects (e.g., spell effects, environmental particles)
- Unity's Audio Mixer for dynamic sound management
Unity's Terrain system for outdoor level creation (e.g., forest levels)

### 4.3 C# Implementation Considerations

- Object-Oriented Programming principles for modular and maintainable code
- Scriptable Objects for flexible data management (e.g., item databases, enemy types)
- Coroutines for time-based events and animations
- Unity's new Input System for responsive player controls
- State machines for managing game states and enemy behaviors

### 4.4 Blender Integration

- Creation of 3D models for characters, environments, and props
- UV mapping and texturing of 3D models
- Rigging and animation of characters and creatures
- Export models and animations in FBX format for Unity compatibility

### 4.5 Performance Optimization

- Implement Level of Detail (LOD) system for distant objects
- Use object pooling for frequently instantiated objects (e.g., projectiles, collectibles)
- Optimize lighting with baked lightmaps for static elements
- Implement occlusion culling to reduce render calls
Use mesh combining techniques for static elements to reduce draw calls

### 4.6 Procedural Generation

- Implement custom algorithms for dungeon layout generation
- Use Unity's ProBuilder for runtime mesh generation and modification
- Develop a modular system for assembling levels from pre-made components

### 4.7 Save System

- Implement a serialization system for saving game progress
- Use Unity's PlayerPrefs for storing simple data
- Consider using JSON serialization for more complex data structures

### 4.8 UI Framework

- Utilize Unity's UI Toolkit for creating responsive and scalable user interfaces
- Implement a UI manager for handling menu navigation and in-game HUD

### 4.9 Networking (if considering future multiplayer features)

- Research Unity's Netcode for GameObjects for potential multiplayer implementation
- Research steam p2p multiplayer connection

### 4.10 Testing and Debugging

- Utilize Unity's built-in profiler for performance analysis
- Implement logging system for tracking errors and game events
- Use Unity's Test Runner for creating and running automated tests

## 5. Art and Audio
### 5.1 Art Style
[To be defined]

### 5.2 Sound Design
[To be defined]

### 5.3 Music
[To be defined]

## 6. User Interface
### 6.1 HUD Elements
[To be defined]

### 6.2 Menu Systems
[To be defined]

## 7. Progression and Economy
### 7.1 Player Progression
[To be defined]

### 7.2 In-game Economy
[To be defined]

## 8. Narrative and Setting
### 8.1 Backstory
[To be defined]

### 8.2 World-building
[To be defined]

## 9. Additional Considerations
### 9.1 Balancing
[To be defined]

### 9.2 Replayability
[To be defined]

### 9.3 Multiplayer Potential
[To be defined]

### 9.4 Accessibility Features
[To be defined]

### 9.5 Post-launch Support
[To be defined]

## 10. Development Roadmap
### 10.1 Milestones
[To be defined]

### 10.2 Testing and QA
[To be defined]

### 10.3 Launch Strategy
[To be defined]
