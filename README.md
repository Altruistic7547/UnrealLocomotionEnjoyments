# AdvanceLocomotionSystemUnrealEngineEnjoyment

## Project Overview
**Advance Locomotion System Unreal Engine Enjoyment** is a personal project focused on exploring and customizing the **Advanced Locomotion System (ALS)** in **Unreal Engine** to create dynamic and interactive gameplay mechanics. 

This project extends the base features of ALS to include advanced interactions, item pickup, and weapon systems, enriching player experiences and gameplay depth.

## Why This Project?
- To implement and customize the **Advanced Locomotion System** for seamless, realistic player movement.

- To develop additional gameplay features such as **item pickup**, **weapon systems**, and **interaction components**.

- To enhance the project with gameplay mechanics like **switches**, **shooting**, and **toggling**.

## Key Features
- **Advanced Locomotion**: Integrated ALS for fluid and realistic player movements including running, jumping, crouching, and transitions.

- **Pickup System**: Custom pickup functionality that allows the player to collect items and integrate them into the inventory.
- **Weapon System**: Developed weapon mechanics that include equipping, aiming, shooting, and reloading, with customizable weapon properties.
- **Interaction Components**: Added versatile interactions such as:
  - **Switches**: Toggleable switches that affect game elements (e.g., doors, lights).
  - **Shooting Mechanisms**: Basic shooting functionality tied to the weapon system for gameplay and combat.
  - **Toggle Interactions**: Components that allow the player to toggle between different states or activate in-game objects.
- **Custom Animations**: Extended ALS with animations for picking up items and interacting with game elements.
- **StylizedCharacter**: Developed modular character styling system that allows player to customise player looks (head, body, hair, clothes) anyhow they want!

## Tools and Technologies
- **Unreal Engine (UE 4.26)**: Game engine used for development.

- **Advanced Locomotion System (ALS)**: Open-source system providing a foundation for advanced character movement.
- **Blueprints**: Visual scripting for quick prototyping and interaction logic.
- **C++**: Used for deeper customizations and performance-critical mechanics.
- **Animation Blueprint**: Customized to include new animations and transitions for interaction.
- **3D Assets**: Custom assets created using **Blender** and integrated into Unreal Engine for realistic props and weapons.

## Project file structure

I have made sure to follow official unreal engine documentation and found out the best practices. One of the best practice is to create seamless reusable and developer friendly file structure.

- Content
    - AdvancedLocomotionSystemV4 <*Prerequisite ALSV4 Project*>
    - Interation
        - Animations
            - AssultRifle <*One example*>
                - aim
                - equip
                - movement
                - shoot
                - other animation sequences
            - Car
            - CloseCombat
            - Cutscene
            - Enemy
            - Handgun
            - Interaction
            - knife
            - movement
            - shotgun
            - submachine
        - Blueprints
            - commentry box
            - interation objects
            -  pawn
            - player controller
            - weapon
                - DamageTypes
                - Structures
                - BP_Weapon
                - other blueprint classes
        - Characters
            - CI_Player
                - mashes
                - materials
                - textures
            - CI_Soldier
            - CI_Zombie
            - CI_ZombieCyber
            - UE4Manniquin
        - Cinemetics
            - sequences
                - level sequence
        - Decals
            - Bullet_Hole
            - Explosion
                - material
                - textures
        - Effects
            - car
            - Droplets
                - partical system 
                - mesh  
            - Gas
            - Impacts
            - JetEngine
        - hud
            - BI_Hud (Blueprint class)
            - BP_Obj_UpdateAmmo (Blueprint class)
            - Hud_Ammo (Widget blueprint)
        - maps
            - level
            - mapbuilddataregistery <*generated via build*>
        - physmat <*Physics Material*>
        - Sounds
        - Weapons
            - AssultRifle
            - Bullet
            - Handgun
            - Shells 
            - Shotgun
                - animation
                - materials
                - mashes
                - textures



## How do you really enjoy this project? 

1. **Download the Project files**: Clone the project files from [this link](https://drive.google.com/drive/folders/1pitPwyUM1bznsUzCCL5sVA_Q-AzhWxtg?usp=sharing).
2. **Open in Unreal Engine**: Open the project in **Unreal Engine** (version 4.26.x or above recommended).
3. **Test the Features**: Use the provided demo level to explore the locomotion, pickup, and interaction features.
4. **Customize and Expand**: Modify the existing components or add new interactions based on your gameplay requirements.
5. Enjoy!


Thank you for reading 😊
 
