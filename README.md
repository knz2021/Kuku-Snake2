# KukuSnake2

KukuSnake2 is an educational browser game that combines the classic Snake game with multiplication practice. Players control a snake while solving multiplication problems and avoiding enemy snakes.

## Features

- Three difficulty levels: Easy, Normal, and Hard
- Interactive snake control using arrow keys or touch gestures
- Multiplication practice with numbers 1-9
- Multiple-choice answer system
- Two AI-controlled enemy snakes
- Responsive design that works on both desktop and mobile devices
- Score tracking system with difficulty multipliers

## Game Rules

1. **Basic Gameplay**
   - Control your snake (green) using arrow keys or touch swipes
   - Collect correct answers to the multiplication questions
   - Your snake grows longer when you collect correct answers
   - Avoid hitting walls (in modes where wall collision is enabled)
   - Avoid hitting enemy snakes (red and orange)
   - Avoid hitting yourself

2. **Scoring System**
   - Easy Mode: 5 points per correct answer (0.5× multiplier)
   - Normal Mode: 10 points per correct answer (1.0× multiplier)
   - Hard Mode: 20 points per correct answer (2.0× multiplier)

3. **Difficulty Levels**
   - Easy Mode:
     - Slower snake speed
     - Slower enemy snakes
     - Lower point multiplier
   - Normal Mode:
     - Medium snake speed
     - Medium enemy snake speed
     - Standard point multiplier
   - Hard Mode:
     - Fast snake speed
     - Fast enemy snakes
     - Higher point multiplier

4. **Game Over Conditions**
   - Collecting an incorrect answer
   - Colliding with an enemy snake
   - Colliding with yourself
   - Hitting the walls (when wall collision is enabled)

## Technical Details

- Built with pure HTML5, CSS3, and JavaScript
- Uses Canvas API for rendering
- No external dependencies required
- Fully responsive design
- Touch-enabled for mobile devices

## How to Play

1. Open the HTML file in a web browser
2. Select your preferred difficulty level
3. Use arrow keys (desktop) or swipe gestures (mobile) to control the snake
4. Solve multiplication problems by guiding your snake to the correct answers
5. Try to achieve the highest score possible!

## Installation

1. Clone the repository or download the HTML file
2. Open the HTML file in any modern web browser
3. No additional installation or setup required

## Browser Compatibility

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Any modern browser with HTML5 Canvas support

## Development

To modify the game:
1. Edit the HTML file using any text editor
2. Adjust game parameters in the JavaScript section
   - `gameSpeed`: Controls snake movement speed
   - `enemySnakes[].speed`: Controls enemy snake movement speed
   - `scoreMultiplier`: Adjusts scoring system
   - Other parameters as needed

## Contributing

Feel free to fork the project and submit pull requests with improvements such as:
- New game features
- Bug fixes
- Performance improvements
- Additional difficulty levels
- UI/UX enhancements
