# GAME_PROGRAM-EX-3

## Aim
To replace the default Third Person Character mesh with a custom skeletal mesh and apply new animations using an Animation Blueprint.

## Procedure

### 1. Import New Character Mesh and Animations
- In the Content Browser, import the new Skeletal Mesh along with its animation FBX files.
- Ensure the mesh is correctly rigged, preferably using the UE4 Mannequin skeleton or a compatible rig.

### 2. Replace the Character Mesh
- Open the ThirdPersonCharacter Blueprint (located in ThirdPersonBP/Blueprints).
- Select the Mesh component.
- In the Details panel, change the Skeletal Mesh to the newly imported character mesh.

### 3. Set the Animation Blueprint
- If an appropriate Animation Blueprint already exists, assign it in the Details → Animation section.
- If not, create a new Animation Blueprint:
  - Right-click in the Content Browser → Animation → Animation Blueprint.
  - Select the correct skeleton.
  - In the AnimGraph, configure State Machines or direct animation nodes.
  - Compile and save the blueprint.

### 4. Preview and Test
- Place the character in the level.
- Press Play to verify idle, walk, run, and other animations responding correctly to movement input.

## Output
<img width="1033" height="703" alt="image" src="https://github.com/user-attachments/assets/fd1d20e1-62b4-41b6-aa72-f5c72d334061" />
<img width="581" height="517" alt="image" src="https://github.com/user-attachments/assets/74204d89-11a3-481e-8136-b31a3e772fba" />
<img width="1036" height="605" alt="image" src="https://github.com/user-attachments/assets/b9fe03e2-c2bc-49af-8df9-92594b72281a" />


## Result
The default Third Person Character mesh was successfully replaced with a custom skeletal mesh, and new animations were applied using an Animation Blueprint. The character now displays the updated appearance and animation set correctly during gameplay.
