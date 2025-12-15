# Tic-Tac-Toe Game

A simple and interactive Tic-Tac-Toe game built with React, allowing two players to compete in a classic 3x3 grid game.

## Features

- **Two-Player Gameplay**: Play as X or O against another player.
- **Editable Player Names**: Customize the names of Player 1 and Player 2.
- **Turn-Based Moves**: Alternating turns with visual indication of the active player.
- **Game Log**: View a history of all moves made during the game.
- **Winner Detection**: Automatically detects and announces the winner based on winning combinations.
- **Draw Detection**: Recognizes when the game ends in a draw.
- **Restart Functionality**: Easily restart the game after completion.

## Technologies Used

- **React 19**: For building the user interface and managing state.
- **Vite**: For fast development and build tooling.
- **CSS**: For styling the game components.

## Installation

1. Clone the repository:

   ```
   git clone <repository-url>
   cd tic-tac-toe
   ```

2. Install dependencies:

   ```
   npm install
   ```

3. Start the development server:

   ```
   npm run dev
   ```

4. Open your browser and navigate to `http://localhost:5173` (or the port shown in the terminal) to play the game.

## Usage

- Enter names for Player 1 (X) and Player 2 (O) if desired.
- Click on an empty square to make a move.
- The game will automatically switch turns and check for a winner or draw.
- View the game log to see the sequence of moves.
- Click the "Rematch" button to start a new game.

## Project Structure

- `src/App.jsx`: Main application component managing game state and logic.
- `src/components/GameBoard.jsx`: Renders the 3x3 game grid.
- `src/components/Player.jsx`: Handles player name editing and display.
- `src/components/Log.jsx`: Displays the history of game turns.
- `src/components/GameOver.jsx`: Shows the game result and restart option.
- `src/winning-combinations.js`: Defines the winning combinations for the game.

## Contributing

Feel free to submit issues or pull requests to improve the game!

## License

This project is open source and available under the [MIT License](LICENSE).
