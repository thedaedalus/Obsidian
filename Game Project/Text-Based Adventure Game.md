# Python Project: Text-Based Adventure Game

## Project Title
The Haunted Mansion

## Description
Create a simple text-based adventure game where the player navigates through a haunted mansion, making choices that lead to different outcomes. The goal is to escape the mansion or find a hidden treasure, avoiding traps and ghosts along the way.

## Features

1.  **Rooms and Navigation:**
    *   Define several rooms (e.g., "Entrance Hall", "Kitchen", "Library", "Bedroom").
    *   Allow the player to move between rooms using commands like `go north`, `go south`, `go east`, `go west`.
    *   Each room should have a description that is displayed when the player enters it.
2.  **Player Inventory:**
    *   Implement an inventory system to hold items the player collects (e.g., "key", "torch", "map").
    *   Allow players to `pick up` items found in rooms.
    *   Allow players to `use` items in specific situations.
3.  **Interactions:**
    *   Objects in rooms that the player can `examine` for clues or to find items.
    *   Simple puzzles, e.g., needing a key to open a locked door.
4.  **Game State and Win/Lose Conditions:**
    *   Track the player's current location, inventory, and health (optional).
    *   Define a clear win condition (e.g., escaping the mansion).
    *   Define lose conditions (e.g., falling into a trap, being caught by a ghost).
5.  **Basic Game Loop:**
    *   A loop that continuously prompts the player for input, processes their command, updates the game state, and provides feedback.

## Concepts to Learn

*   **Variables:** Storing player name, current room, inventory.
*   **Data Structures:**
    *   Dictionaries: To represent rooms (e.g., `room = {"name": "Kitchen", "description": "A dusty old kitchen.", "exits": {"north": "Dining Room"}, "items": ["knife"]}`).
    *   Lists: For the player's inventory, items in a room.
*   **Functions:** To encapsulate game logic (e.g., `move_player()`, `display_room()`, `pick_up_item()`).
*   **Conditional Statements (`if`/`elif`/`else`):** For checking player commands, win/lose conditions, and item usage.
*   **Loops (`while`):** For the main game loop.
*   **Input/Output (`input()`, `print()`):** For player commands and game narration.
*   **String Manipulation:** Parsing player commands (e.g., splitting "go north" into "go" and "north").

## Bonus Challenges (for extended learning)

*   **NPCs (Non-Player Characters):** Add friendly or hostile characters the player can interact with.
*   **Combat System:** A simple turn-based combat system if the player encounters a hostile entity.
*   **More Complex Puzzles:** Multi-step puzzles requiring multiple items or clues.
*   **Saving/Loading Game:** Use file I/O to save and load game progress.
*   **Error Handling:** Improve robustness by handling invalid player commands gracefully.
*   **"Look" Command:** Allow the player to `look` at a room to get a more detailed description of objects present.
*   **Time/Turn Limit:** Add a sense of urgency to the game.