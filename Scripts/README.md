## Player Movement:

1. Purpose: Detects and handles the movement of the Doofus (player character).
2. Components:
     - CharacterController for handling character movement.
      - Parameters for speed, gravity, and jump height.
      - Ground check using a sphere cast to determine if the player is grounded.
3. Controls:
    - Use arrow keys or WSAD for movement.
    - Jump with the spacebar.
4. Behavior:
   - Controls Doofus movement based on user input.
   - Implements jumping functionality.
   - Applies gravity and ensures proper ground detection.

## Mouse Movement:

1. Purpose: Manages mouse input to control the camera's rotation.
2. Controls:
   - Move the mouse to look around.
3. Components:
   - `Cursor.lockState` to lock and hide the cursor.
4. Behavior:
   - Controls camera rotation around the X and Y axes.
   - Applies sensitivity and clamps rotation to avoid over-rotation.
## Selection Manager:
1. Purpose: Handles object selection when the mouse hovers over interactable objects.
2. Components:
   - `Raycast` to detect objects under the mouse cursor.
   - Interaction info UI for displaying object information.
3. Behavior:
   - Uses raycasting to detect objects in the scene.
   - Displays information about the interactable object when detected.

## Interactable Object:

1. Purpose: Represents objects that can be interacted with.
2. Components:
    - `ItemName` to store the name of the interactable object.
3. Behavior:
   - Provides a method (GetItemName) to retrieve the name of the interactable object.

## AI Movement:

1. Purpose: Controls the movement of AI characters.
2. Components:
   - `Animator` for handling animations.
   - Parameters for movement speed and timers.
3. Behavior:
   - Randomly selects a direction for the AI to move.
   - Handles waiting and walking phases with appropriate animations.
   - Chooses a new direction after completing a walk cycle.

These scripts collectively contribute to the player and AI character movements, camera control, object selection, and interaction within the Unity game environment.
