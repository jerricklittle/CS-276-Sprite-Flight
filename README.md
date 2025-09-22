# Jerrick Little's Sprite Flight

## Play the Game
**Unity Play Link**: https://play.unity.com/en/games/bf6fb89e-c533-4130-9930-d09a098cf7ed/jerrick-littles-sprite-flight

## Game Overview
Sprite Flight is a 2D survival game built in Unity. The player controls a spaceship and must avoid bouncing sprites for as long as possible to achieve the highest score.
The game grows more difficult as sprites collide with each other and walls, testing the users reflexes.

### Controls
- Left Mouse Click: Move the spaceship.

### How to Play
Survive as long as possible by dodging sprites.

Your score increases based on the time you remain alive.

Colliding with a sprite ends the game.

## Base Game Implementation

### Completion Status
- [x] Player movement and controls
- [x] Obstacle spawning system
- [x] Collision detection
- [x] Score system
- [x] Game over state

### Known Bugs
- Player movement is buggy and teleports around UI
- Player rotates around cursor

### Limitations
- No levels or progression system beyond increasing sprite difficulty.

## Extensions Implemented

### 1. Cohesive Color Scheme (2 points)
**Implementation**: Altered the color of sprites, borders, and spaceship.
**Game Impact**: Creates a visually appealing effect
**Technical Details**: Each item has a unique color code.
**Known Issues**: N/A

### 2. Reactive Booster Flame (6 points)
**Implementation**: Created a game object that activates when the user clicks.
**Game Impact**: Gives the game more realism
**Technical Details**: Added a condition statement in the update() of the playercontroller script.
**Known Issues**: N/A

### 3. Increase Game Difficulty Over Time (5 points)
**Implementation**: Game gets more difficult as sprites bounce off of things.
**Game Impact**: Makes the game progressively harder
**Technical Details**: Changed the bounciness level in my physics slightly so they will become faster as they collide.
**Known Issues**: N/A

### 4. Destroy Borders on Game End (4 points)
**Implementation**: Removes border when a user collides with sprite or border
**Game Impact**: Helps visually confirm game over.
**Technical Details**: Within the collision script, I turned the borders off when the player collides.
**Known Issues**: N/A

### 5. Sound Effects (5 points)
**Implementation**: Added background music and an explosion when user explodes.
**Game Impact**: These make the game more intense
**Technical Details**: Used the audio from the tutorial to the audio source option in the hierarchy.
**Known Issues**: N/A

### 6. Add Ambient Particles (4 points)
**Implementation**: Added background particles to look like space
**Game Impact**: Adds realism to the game as we are flying through space.
**Technical Details**: Used the particle system to add particles that float around the UI.
**Known Issues**: N/A


## Credits
- All assets (sprites, sounds, and particle effects) are from Unity’s built-in resources or project tutorial materials.

## Reflection
**Total Points Claimed**: [Base: 80% + Extensions: 26% = 106%]
**Challenges**: The most difficult part of this project was debugging the player movement, which still does not behave as expected. Another challenge was creating and attaching the booster
flame, as it required me to learn how to properly define and use variables in C#. Overall, this project helped me become more comfortable with Unity’s essential functions, collision and 
physics system, and scripting in C#.
**Learning Outcomes**: Throughout this project, I learned how to navigate Unity's interface and resources to effectively use the physics and collision systems. Furtermore, I was
able to learn how to do some scripting in C#. These helped me create an immersive game experience that will be enjoyable.
