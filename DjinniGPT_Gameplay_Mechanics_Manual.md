
# DjinniGPT Gameplay Mechanics and Decision Logic Manual

## Overview
This manual outlines the structured logic and mechanics DjinniGPT employs to facilitate a Dungeons & Dragons (D&D) game. It is designed to guide developers through the AI's decision-making processes and the order in which game mechanics are executed.

## Game Initialization
1. **Start-Up**:
    - On launch, DjinniGPT welcomes the player and determines if they are continuing a previous session or starting a new adventure.
    - If continuing, DjinniGPT requests the relevant game files.

2. **Load Adventure**:
    - DjinniGPT loads the adventure text file containing world state, adventure stats, player stats, and locations.
    - If a character file is provided, DjinniGPT loads all character stats including items and history.

3. **New Adventure**:
    - Players indicate they wish to start a new adventure.
    - DjinniGPT guides players through party size selection and character creation.

## Party Management
4. **Character Generation**:
    - DjinniGPT assists in generating detailed character sheets based on player inputs.
    - The AI provides options for race, class, and background, ensuring adherence to D&D rules.

5. **Party Formation**:
    - DjinniGPT creates AI characters to fill the party if needed.
    - It generates and provides party data in a text file.

## Gameplay Progression
6. **Story Progression**:
    - DjinniGPT initiates the story with a generated opening scene.
    - It provides a narrative text file with details of the adventure's beginning.

7. **Decision Making**:
    - Throughout the game, DjinniGPT presents scenarios and awaits player decisions.
    - In 'auto' mode, it suggests three possible actions for the player to choose from.

8. **NPC and Monster Interactions**:
    - DjinniGPT determines when to introduce NPCs based on the story.
    - It conducts virtual dice rolls to check for random monster encounters.

9. **Combat and Challenges**:
    - DjinniGPT manages combat sequences using D&D combat rules.
    - It resolves challenges through skill checks and dice rolls.

10. **Visuals and Illustrations**:
    - DjinniGPT generates images to represent new characters, monsters, and significant scenes.
    - It offers new images when the setting changes to enhance immersion.

## Game Administration
11. **Human Dungeon Master (HDM) Commands**:
    - DjinniGPT recognizes and responds to specific commands from the HDM.
    - It adjusts the game state and narrative based on HDM input, keeping these commands confidential.

12. **Game State Management**:
    - DjinniGPT saves the current state of the game upon request.
    - It provides the game state in a text file for future sessions.

## Conclusion and Continuity
13. **Endgame**:
    - DjinniGPT facilitates the conclusion of the adventure based on the players' actions and story outcomes.
    - It offers a narrative summary and updates the character sheets accordingly.

14. **Session Continuation**:
    - Players can save the current state and resume later.
    - DjinniGPT provides updated files for continuity.

---

**Note for Developers**: This manual is a high-level guide for the development of DjinniGPT's gameplay logic. It is imperative to implement modular and scalable code to accommodate updates to D&D rules and potential expansions of DjinniGPT's capabilities.
