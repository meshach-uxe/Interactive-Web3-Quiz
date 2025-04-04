## Overview
Web3 Quiz Adventure is an interactive web-based quiz game designed to educate users about Web3 concepts, blockchain technology, and decentralized applications. The game features multiple levels of increasing difficulty, each containing a set of questions that test the player's knowledge. Players can track their progress, view a scoreboard, and retry levels to improve their scores.

## Features
- **Dynamic Quiz Levels**: The quiz consists of 10 levels, each with 10 questions. Questions become progressively harder as players advance.
- **Interactive Feedback**: Players receive immediate feedback on their answers, including explanations for correct and incorrect responses.
- **Scoreboard**: A persistent scoreboard tracks the highest level achieved by each player.
- **Responsive Design**: The game is optimized for both desktop and mobile devices.
- **Animations**: Visual feedback for correct and incorrect answers using CSS animations.
- **Local Storage**: Player scores are saved locally using `localStorage`.

## How It Works
1. **Start Screen**: Players enter their name and begin the quiz.
2. **Quiz Screen**: Players answer multiple-choice questions. Correct answers are highlighted in green, and incorrect answers in red.
3. **Level Summary**: At the end of each level, players see their score and a message indicating whether they passed or need to retry.
4. **Final Screen**: Players who complete all 10 levels are congratulated as Web3 Masters.
5. **Scoreboard**: Players can view a ranked list of scores, showing the highest level achieved by each participant.

## Technologies Used
- **HTML**: Structure of the application.
- **CSS**: Styling and animations for a visually appealing interface.
- **JavaScript**: Core logic for quiz functionality, including question handling, score tracking, and local storage.

## File Structure
- **index.html**: Main HTML file containing the structure and embedded JavaScript and CSS.
- **Local Storage**: Used to persist scoreboard data across sessions.

## Key Components
### HTML
- **Start Screen**: Allows players to input their name and start the quiz.
- **Quiz Screen**: Displays questions, options, and feedback.
- **Level Summary**: Shows results for the current level and options to proceed or retry.
- **Final Screen**: Congratulates players who complete all levels.
- **Scoreboard**: Displays a ranked list of players and their highest levels.

### CSS
- **Animations**: 
  - Gradient background animation for the main interface.
  - Correct and incorrect answer animations for visual feedback.
- **Responsive Design**: Ensures compatibility with various screen sizes.

### JavaScript
- **Question Handling**: Dynamically loads and shuffles questions for each level.
- **Answer Validation**: Checks player answers and provides feedback.
- **Score Tracking**: Tracks player scores and updates the scoreboard.
- **Local Storage**: Saves and retrieves scoreboard data.

## How to Play
1. Enter your name on the start screen and click "Start Quiz."
2. Answer the multiple-choice questions by selecting the correct option.
3. Review feedback and proceed to the next question or level.
4. Complete all 10 levels to become a Web3 Master.
5. View the scoreboard to compare your progress with others.

## Customization
- **Questions**: Add or modify questions in the `questions` array in the JavaScript section.
- **Styling**: Update the CSS to change the appearance of the quiz.
- **Levels**: Add more levels or adjust the difficulty by modifying the `questions` array.

## Future Enhancements
- **Backend Integration**: Store scores on a server for global leaderboards.
- **User Authentication**: Allow players to create accounts and save progress across devices.
- **Advanced Topics**: Add more levels covering advanced Web3 concepts like sharding, zero-knowledge proofs, and layer 2 solutions.

## License
This project is open-source and available for educational purposes. Feel free to modify and distribute it as needed.
