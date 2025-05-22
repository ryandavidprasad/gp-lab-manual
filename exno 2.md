# EXP-02: Create A Player Movement Using Pawn, Collectable, Player Health And Score.
## Date:12/3/25
## Aim:
To Create a player movement using pawn, collectible, player health and score.

## Procedure To Create and Destroy the coin:
1.Create Player Character with Movement
Create a Blueprint Class based on Character (e.g., BP_PlayerCharacter).
Add a Camera and Spring Arm for third-person or first-person view.
In the Event Graph, add input bindings for movement:
*MoveForward, *MoveRight using InputAxis events.
Use Add Movement Input for directional movement.
2. Create Collectable Item
Create a new Actor Blueprint (e.g., BP_Collectable).
Add a Static Mesh and Sphere Collision component.
On BeginOverlap with player:
Destroy the collectable.
Call a custom event or function on the player to increment score or health.
3. Implement Health System
In BP_PlayerCharacter, add a Health variable (e.g., float, default: 100).
Create a TakeDamage function to subtract from Health.
Optionally, implement logic to handle 0 health (e.g., death or respawn).
4. Implement Score System
Add a Score variable (int) in BP_PlayerCharacter.
When a collectable is picked up, increase the score.
Display score using UMG Widget:
Create a Widget Blueprint (e.g., W_HUD).
Add Text Blocks bound to Health and Score variables.
5. Setup Game Mode
Create a new Game Mode Blueprint.
Set BP_PlayerCharacter as the default pawn.
Set the HUD widget in the Game Mode’s BeginPlay using Create Widget and Add to Viewport.

## Output:

![image](https://github.com/user-attachments/assets/c0332ccc-0500-41ea-9487-d33bc5db0970)

![image](https://github.com/user-attachments/assets/527bc441-b77b-4336-9964-2bea40523699)

![image](https://github.com/user-attachments/assets/5cfd3e5b-8e52-4d85-a1d9-bfd893b36c06)

## Result:
Thus, To Create a player movement using pawn, collectible, player health, and score created and developed by unreal Engine.
