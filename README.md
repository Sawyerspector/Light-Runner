# Light Runner

Fast-paced third-person platformer built in Unreal Engine 5, focused on grappling, movement mastery, and dynamic light-based traversal.

---

## Project Overview

**Light Runner** is a third-person platforming game built in Unreal Engine 5. The game combines fast, fluid movement with challenging traversal through dark, atmospheric environments.

Players use jumping, dashing, and grappling to navigate platforming levels as quickly as possible. Levels follow a clear overall path while providing multiple ways to traverse obstacles, rewarding movement mastery and faster routes.

A central mechanic connects traversal directly to the environment: **grapple points are only accessible while illuminated**. Lights dynamically turn on and off, forcing the player to time grapples and adapt as traversal routes become available or inaccessible.

---

## Gameplay Systems

### Grappling
- Custom grappling system for rapid traversal
- Pulls the player toward valid grapple targets
- Preserves fast, momentum-focused movement
- Integrates with vertical platforming and level geometry

### Dynamic Light-Based Traversal
- Grapple targets alternate between illuminated and dark states
- Illuminated targets can be grappled
- Dark targets become inaccessible
- Creates timing-based traversal challenges and changing routes

### Movement
- Fast third-person platforming
- Dash ability with cooldown
- Grappling and momentum-based traversal
- Movement designed to be accessible but difficult to master

### Levels & Progression
- Multiple platforming levels and traversal challenges
- Checkpoint-based respawning for quick retries
- Multiple possible routes through primarily linear environments
- Timer encourages faster and more efficient runs

### UI & Feedback
- Grapple and dash indicators
- Level timer
- Movement and environmental audio feedback
- Lighting used for both atmosphere and gameplay communication

---

## Visual Design

Light Runner uses a **dark, ornate, old-world aesthetic** built around dramatic lighting. Candles and lamps illuminate important areas of otherwise dark environments, serving as both visual guidance and functional parts of the movement system.

---

## Design Goals

- Create fast, responsive movement that rewards mastery
- Integrate lighting directly into gameplay
- Encourage players to optimize traversal routes
- Keep retries fast through checkpoint-based respawning
- Combine an old-world atmosphere with high-speed platforming

---

## Tools & Technologies

- **Unreal Engine 5**
- **Blueprints**
- Character movement and physics systems
- Dynamic lighting
- UI / HUD systems
- Level design
- Animation and audio integration
