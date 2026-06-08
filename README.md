# TESTER_1

A survival game engine built in C++ that handles all game logic, with graphics rendering managed by Unreal Engine.

## Features

### Player Mechanics
- **Movement** - Character locomotion and traversal
- **Looting** - Item collection and interaction
- **Weapon Functions** - Combat system and weapon handling
- **Player Storage** - Inventory management
- **Health System** - Damage, healing, and survival mechanics
- **Stamina System** - Energy management for actions

### Vehicle System
- **Realistic Car Simulation**
  - 4WD (All-Wheel Drive) physics
  - Differential Lock system
  - Towing capability for trailers
  - Advanced physics simulation
  - **Collision Detection** - Vehicle-to-vehicle and vehicle-to-environment collisions with realistic damage
  - **Damage System** - Parts degradation (engine, wheels, suspension)
  - **Fuel System** - Fuel consumption and tank management

### Terrain & Environment
- **Terrain Deformation** - Dynamic ground deformation from vehicle tracks and impacts
- **Environmental Hazards** - Obstacles, cliffs, water bodies
- **Weather System** - Dynamic weather affecting visibility and traction
- **Mud/Debris** - Realistic ground interaction affecting vehicle traction

### Interactive Objects
- Door and chest opening mechanisms
- Resource scavenging (water, food, supplies)
- Craftable items and building materials

### Combat & Survival
- **NPC Interaction** - NPCs for trading, missions, and encounters
- **Enemy AI** - Hostile creatures or survivors
- **Hunger & Thirst System** - Resource consumption mechanics
- **Environmental Damage** - Radiation, cold, heat exposure
- **Day/Night Cycle** - Dynamic lighting and gameplay changes

### Additional Suggested Features

#### Gameplay Mechanics
- **Crafting System** - Create weapons, tools, and survival items
- **Quest/Mission System** - Objectives and progression
- **Save/Load System** - Game state persistence
- **Multiplayer Support** - Co-op or PvP gameplay (optional)

#### Physics & Realism
- **Water Physics** - Buoyancy, swimming, water resistance
- **Wind Effects** - Affects movement, visibility, and vehicle handling
- **Gravity & Slope Physics** - Realistic vehicle behavior on inclines
- **Particle Effects** - Dust clouds, debris, explosions

#### UI/UX
- **HUD System** - Health, stamina, inventory displays
- **Map/Navigation** - In-game map with markers
- **Menu System** - Settings, pause menu, main menu
- **Tutorial/Onboarding** - Player guidance

#### Performance
- **LOD (Level of Detail)** - Optimize rendering
- **Pooling System** - Efficient resource management
- **Network Optimization** (if multiplayer)

## Technology Stack
- **Language:** C++
- **Graphics Engine:** Unreal Engine
- **Physics:** Unreal Physics Engine

## Project Status
In early development and testing phase.

## Next Steps
1. Implement collision detection and response systems
2. Add terrain deformation mechanics
3. Develop vehicle damage system
4. Create basic NPC AI
5. Build crafting and inventory UI
