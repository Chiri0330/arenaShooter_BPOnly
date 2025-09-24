# arenaShooter_BPOnly

## Description
This project is a simple **Arena Shooter game** built in Unreal Engine. It is a **Player vs AI** setup where the player fights against an enemy AI in a redesigned arena map.  

Originally, the project included a Rubik’s Cube element, but I removed it because it caused lag and memory issues. I also fixed bugs with scoring and elimination: previously the player score and AI elimination were not updating properly. These issues are now resolved through fixes in **Blueprints** and **class details**, making the gameplay flow correctly.

---

## Features
- **Player vs AI Combat**: AI uses a Behavior Tree and Blackboard to patrol, detect, and attack the player.  
- **Bug Fixes**: Player scoring and AI elimination now update correctly.  
- **Redesigned Map**: Optimized environment for smoother gameplay.  
- **Pickups**: Health and Shield pickups are available for both player and AI.  
- **Blueprint Systems**: Organized event graphs for AI and Player (movement, shooting, damage, health, and shield).  
- **Projectiles**: Player and AI each have working projectile systems with damage feedback.  

---

## Screenshots
Key screenshots of the project (found in the repo under `/Screenshots`):

1. **AI Setup**  
   ![AI Blueprints](Screenshots/arenaShooter_AI_Bp.jpg)  
   *AI Blackboard and Behavior Tree controlling enemy actions.*

2. **AI Behavior Tree**  
   ![AI Behavior Tree](Screenshots/arenaShooter_AI_BT.jpg)  
   *Logic for AI movement, patrolling, focusing, and shooting.*

3. **AI Event Graph**  
   ![AI Graph](Screenshots/arenaShooter_AI_GraphBP.jpg)  
   *AI health, respawn, projectile, and scoring logic.*

4. **Materials**  
   ![Materials](Screenshots/arenaShooter_Materials.jpg)  
   *Custom materials for arena cubes and floor.*

5. **Pickups**  
   ![Pickups](Screenshots/arenaShooter_PickupsBp.jpg)  
   *Health and shield pickups with materials and blueprints.*

6. **Player Setup**  
   ![Player Blueprint](Screenshots/arenaShooter_PlayerBp.jpg)  
   *Player character blueprint setup.*

7. **Player Damage Graph**  
   ![Player Damage Graph](Screenshots/arenaShooter_PlayerBp_DamageGraph.jpg)  
   *Damage logic for player, connected to health and shield systems.*

8. **Player Full Setup**  
   ![Player Graph](Screenshots/arenaShooter_PlayerBp_Graph.jpg)  
   *Organized player event graph (movement, scoring, respawn, pickups).*

9. **Player Health Graph**  
   ![Player Health](Screenshots/arenaShooter_PlayerBp_Health.jpg)  
   *Health and respawn logic for player character.*

10. **Player Movement Graph**  
   ![Player Movement](Screenshots/arenaShooter_PlayerBp_MoveGraph.jpg)  
   *Player input handling for forward, strafe, and rotation.*

---

## Tools Used
- Unreal Engine (Blueprints, AI Behavior Trees, Blackboards)  
- GitHub for version control  
- Adobe Photoshop (materials/icons)

---

## Future Plans
- Add more AI variations (different behaviors or difficulty).  
- Implement time-based scoring system.  
- Add new map layouts for variety.  
