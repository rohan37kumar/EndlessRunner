# Endless Runner

## Created by: cranekyle03

### Overview
"Endless Runner" is an engaging and dynamic game where players navigate through an endless track, avoiding obstacles and collecting coins. The game features a simple yet addictive mechanic that keeps players on their toes as they switch lanes and strive for a high score.

### Game Mechanics

1. **Player Movement**:
   - The player character can switch between three lanes (left, middle, right) by swiping on the screen or using mouse input.
   - The player runs continuously forward, and lane switching is achieved through touch or mouse swipes.

2. **Lane Switching**:
   - When the player swipes left or right, the character smoothly transitions to the adjacent lane.
   - A slight rotation effect is applied during lane switching to enhance the visual feedback, making it appear as if the player is leaning into the new lane.

3. **Scoring System**:
   - Players collect coins scattered along the track. Each coin collected increments the score.
   - The score is displayed on the UI, allowing players to track their progress.

4. **Game Over Condition**:
   - The game ends when the player collides with an obstacle.
   - Upon game over, the player's score is displayed, and the game reloads after five seconds.

5. **Track Management**:
   - The game features an endless track that spawns new segments as the player progresses.
   - Old track segments are automatically destroyed to optimize performance and maintain a smooth gameplay experience.

### Game Flow

1. **Start Screen**:
   - The game begins with a start screen featuring a button to initiate gameplay.
   - Players can tap the start button to begin their adventure.

2. **Gameplay**:
   - Once the game starts, the player character begins running automatically.
   - Players can switch lanes to avoid obstacles and collect coins.
   - The UI updates the score in real-time as coins are collected.

3. **Game Over**:
   - If the player collides with an obstacle, the game pauses, and a game over screen appears.
   - The final score is displayed, and the game will restart after a short duration.

### Technical Details

- **Scripts**:
  - `GameManager.cs`: Manages the overall game state, including starting and ending the game.
  - `PlayerController.cs`: Handles player movement, lane switching, and animations.
  - `TrackManager.cs`: Manages the spawning and movement of track segments.
  - `UIManager.cs`: Controls the user interface, including score display and game over screen.
  - `SpawnTrigger.cs`: Triggers the spawning of new track segments.
  - `AutoDestroy.cs`: Automatically destroys track segments that are no longer needed.

### Conclusion
"Endless Runner" is designed to provide a fun and challenging experience for players of all ages. With its simple mechanics and engaging gameplay, it encourages players to improve their skills and achieve higher scores. Enjoy the thrill of running, dodging, and collecting in this endless adventure!
Happy Playing... -KC
