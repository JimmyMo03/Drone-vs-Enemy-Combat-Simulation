# Drone vs Enemy Combat Simulation

## Overview
A 3D Unity combat prototype where the player controls a drone, launches missiles at targets, and fights an enemy soldier with patrol and combat behaviors.

## Features
- **Drone movement:** Forward and backward flight, yaw rotation, ascending and descending.
- **Camera:** Smooth follow camera that rotates with the drone.
- **Player weapons:** Launches missiles that travel in a straight line.
- **Destructible targets:** Targets have configurable health and are destroyed when their health reaches zero.
- **Enemy patrol:** The enemy soldier patrols between configured waypoints using Unity's NavMesh.
- **Enemy detection:** The soldier detects the drone within a configurable range.
- **Enemy aiming and shooting:** The soldier turns toward the drone and fires straight-line projectiles.
- **Drone health:** Enemy hits reduce the drone's health; the drone is disabled when its health reaches zero.
- **Feedback:** Explosion particles, sound effects, and drone damage feedback.

## Controls
| Key | Action |
|---|---|
| W | Fly forward |
| S | Fly backward |
| A | Rotate left |
| D | Rotate right |
| E | Ascend |
| Q | Descend |
| Space | Fire missile |

## How to Run
1. Open the project in the Unity Editor version compatible with the project.
2. Open the main gameplay scene.
3. Ensure the NavMesh is baked and the enemy patrol waypoints are assigned.
4. Press **Play** to start the simulation.


## Known Bugs and Limitations

- **Basic enemy detection:** The enemy detects the drone based on distance only; obstacles do not block detection.
- **Straight-line projectiles:** Both player and enemy missiles travel in straight lines after firing and do not track moving targets.
- **Simplified enemy AI:** The enemy patrols between predefined waypoints, then stops and engages the drone when detected. It does not resume patrolling after combat.
- **Placeholder assets:** The soldier, drone, and projectile models may use basic shapes rather than production-ready assets.
- **Limited combat feedback:** Health and damage feedback are basic, and the prototype does not include a complete mission progression or restart system.
- **Prototype scope:** The simulation focuses on core movement, shooting, destructible targets, and basic enemy AI rather than a fully developed game.

## Notes
This project is a prototype focused on core movement, projectile mechanics, target destruction, and basic enemy AI. Models and effects are placeholders.

## Screenshots
![Main Gameplay](1.jpeg)

![Combat](2.jpeg)

![Enemy AI](3.jpeg)

![Engaging Combat](4.jpeg)
