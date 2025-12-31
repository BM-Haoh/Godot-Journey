# First push: 12/31/2025
- What's in:
  - Nodes: Level, Gate, Box, Bed, Player, Drone, Laser, grenade
- Work done:
  - In Level: Setted an gate with an Area2D that tells if someone has stepped in; Setted a Player.
  - In Player: Rotation towards the mouse position; movement; Primary and Secondary actions (laser and grenade)
  - In "Projectiles": laser rotation and direction (depends on player); Grenade physics, grenade direction (depends on player)
  - In "Objects": Box and Bed are StaticBodys2D, so them work as barriers basically. Gate has the Area2D feature mentioned before.
  - In Drone: not implemented yet; Previusly was a simple CharacterBody2D that only moves to left.
