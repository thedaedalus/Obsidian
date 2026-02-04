# Text-Based Adventure Game Development Checklist

This checklist outlines the major steps for building your "Haunted Mansion" text-based adventure game. Mark items as you complete them!

## Phase 1: Planning and Setup

-   [ ]  **Conceptualise Game World:**
    -   [ ]  Draw a map of your mansion rooms and connections.
    -   [ ]  List descriptions, initial items, and special conditions for each room.
-   [ ]  **Design Data Structures:**
    -   [ ]  Plan how to represent rooms (unique ID, description, exits, items).
    -   [ ]  Plan how to represent player state (current location, inventory).
    -   [ ]  Decide on item representation (e.g., simple strings or complex objects).

## Phase 2: Core Game Logic

-   [ ]  **Implement Main Game Loop:**
    -   [ ]  Set up a continuous loop for game interaction.
    -   [ ]  Inside the loop, display the current room's description.
    -   [ ]  Inside the loop, prompt the player for input.
    -   [ ]  Implement a mechanism to check for game end (win/lose) and break the loop.
-   [ ]  **Display Current Room Information:**
    -   [ ]  Function to print the room's description.
    -   [ ]  Function to list items currently in the room.

## Phase 3: Player Interaction and Actions

-   [ ]  **Handle Player Input:**
    -   [ ]  Get input from the player using `input()`.
    -   [ ]  Parse the input to identify the action and any associated object/direction.
-   [ ]  **Implement Basic Actions:**
    -   [ ]  **Movement (`go [direction]`):**
        -   [ ]  Check if the chosen direction is a valid exit from the current room.
        -   [ ]  Update the player's current location if valid.
        -   [ ]  Provide feedback for valid/invalid moves.
    -   [ ]  **Take Item (`take [item]`):**
        -   [ ]  Check if the item exists in the current room.
        -   [ ]  Move the item from the room's inventory to the player's inventory.
        -   [ ]  Provide feedback on success or failure.
    -   [ ]  **Examine (`examine [object/room]`):**
        -   [ ]  Provide a description of the current room or a specific item if it's in the room or inventory.
    -   [ ]  **Inventory (`inventory`):**
        -   [ ]  Display all items currently held by the player.
-   [ ]  **Implement Win/Lose Conditions:**
    -   [ ]  Define and check for winning conditions (e.g., reach specific room, collect specific item).
    -   [ ]  Define and check for losing conditions (e.g., entering trap room, specific negative action).
    -   [ ]  Provide appropriate messages when the game ends.

## Phase 4: Refinement and Advanced Features (Bonus Challenges)

-   [ ]  **Error Handling:**
    -   [ ]  Gracefully handle unknown commands.
    -   [ ]  Handle invalid item/direction choices.
-   [ ]  **`Use` Command (`use [item]`):**
    -   [ ]  Implement conditional logic for using specific items in specific contexts.
-   [ ]  **NPCs (Non-Player Characters):**
    -   [ ]  Add characters with whom the player can interact.
-   [ ]  **Combat System:**
    -   [ ]  Develop a simple turn-based combat mechanism.
-   [ ]  **Saving/Loading Game:**
    -   [ ]  Implement functionality to save and load game progress to/from a file.
-   [ ]  **"Look" Command:**
    -   [ ]  Add a more detailed "look" command for closer inspection of rooms or items.