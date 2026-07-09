An **Actor** is an entity that has **agency** within the game world.

An Actor can initiate gameplay actions on its own, whether controlled by the player, AI, or another system. It owns gameplay state and can expose capabilities to other systems.

Examples:
- Player
- Zombie
- NPC
- Animal
- Automated Turret
- Automated Drone
- Automated Vehicle etc...
- Any automated entity/gameobject

**Rule of thumb:**  
> If it can *"decide"* to perform an action instead of only reacting to one, it's probably an Actor.

>A door, button, or chest is **not** an Actor because it only reacts to external input. It has no agency of its own, it doesn't initiate gameplay actions, nor is it controlled by a player or an AI.