
# Tic Tac Toe Game

Welcome to the Tic Tac Toe Game repository! This is a simple web-based implementation of the classic Tic Tac Toe game using React. Players can take turns clicking on the squares of the grid to make their moves and compete against each other to achieve three in a row and win the game.

## Table of Contents
- [Features](#features)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Roadmap of Future Improvements](#roadmap-of-future-improvements)
- [Contributing](#contributing)
- [License](#license)

## Features

- Interactive game board where players can take turns by clicking on the squares.
- Real-time display of the next player's turn and the game's outcome (winner or draw).
- Future Improvements:
  1. **Highlight Winning Combination**: Enhance the game's visual feedback by drawing a line through all the squares of the winning combination when a player wins the game.
  2. **Toggle Game Board Size**: Allow users to toggle the game board size between 3x3, 4x4, and 5x5 grids to add more complexity and challenge to the game.

## Getting Started

To run the Tic Tac Toe Game on your local machine, follow the steps below:

1. Clone the repository to your local machine using Git:

   ```bash
   git clone https://github.com/titomazzetta/tic-tac-toe-game.git
   cd tic-tac-toe-game
   ```

2. Since the game is built with React, you'll need to set up a local server to see it in action. You can use any server of your choice, such as live-server, http-server, or even set up a more complex development environment like using Node.js and create-react-app.

Open your web browser and navigate to the local server's URL (e.g., http://localhost:8000 or the port specified by your local server) to access the Tic Tac Toe Game.

2. Open the `standalone.html` file in your preferred web browser.

That's it! You should now see the Tic Tac Toe Game running in your browser.

## Usage

- Click on any empty square in the grid to make your move.
- The game will display the current player's turn and the winner once the game is won.
- To start a new game, simply refresh the page.

## Roadmap of Future Improvements

We have some exciting features planned for the future to enhance the gaming experience:

1. **Highlight Winning Combination**:
   - Feature Description: Enhance the game's visual feedback by drawing a line through all the squares of the winning combination when a player wins the game.
   - Implementation: After determining the winner, identify the winning squares' positions in the grid. Utilize CSS to draw a line connecting these squares and provide visual feedback to the player.

2. **Toggle Game Board Size**:
   - Feature Description: Allow users to toggle the game board size between 3x3, 4x4, and 5x5 grids to add more complexity and challenge to the game.
   - Implementation: Introduce a button or a dropdown menu to the game interface, enabling users to select their desired board size. Dynamically adjust the grid creation logic and winning combination checks based on the selected size.

We are always open to new ideas and contributions from the community. Feel free to submit suggestions or contribute to the project.

## Contributing

We welcome contributions to improve the Tic Tac Toe Game! To contribute, follow these steps:

1. Fork the repository on GitHub.
2. Create a new branch with a descriptive name for your feature or bug fix.
3. Commit your changes and push them to your fork.
4. Submit a pull request to the `main` branch of the original repository.
5. Wait for the code review and feedback.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Thank you for checking out our Tic Tac Toe Game repository! We hope you enjoy playing the game and find the project interesting. If you have any questions or feedback, feel free to reach out. Happy gaming!
