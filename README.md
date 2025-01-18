# React Tic-tac-toe Game

A modern implementation of the classic Tic-tac-toe game built with React. This interactive game features a dynamic game board, move history tracking, and the ability to review previous moves.

## Features

- 🎮 Interactive 3x3 game board
- 📝 Move history tracking
- ⏪ Time travel feature to review previous moves
- 🏆 Automatic winner detection
- 🔄 Game state management with React hooks
- 📱 Responsive design

## Technologies Used

- React 18+
- CSS3
- Create React App
- JavaScript ES6+

## Getting Started

### Prerequisites

- Node.js (version 14.0.0 or higher)
- npm (version 6.0.0 or higher)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/react-tictactoe.git
```

2. Navigate to the project directory:
```bash
cd react-tictactoe
```

3. Install dependencies:
```bash
npm install
```

4. Start the development server:
```bash
npm start
```

5. Open your browser and visit `http://localhost:3000`

## How to Play

1. The game starts with Player X
2. Click on any empty square to make a move
3. Players alternate between X and O
4. The first player to get three of their symbols in a row (horizontally, vertically, or diagonally) wins
5. Use the move history list on the right to jump to any previous game state

## Project Structure

```
├── public/
│   └── index.html
└── src/
    ├── App.js         # Main game logic and components
    ├── App.css        # Styling
    ├── index.js       # Entry point
    └── index.css      # Global styles
```

## Game Components

- `Game`: Main component that manages game state and history
- `Board`: Renders the game board and handles moves
- `Square`: Individual square component for the game board

## Contributing

1. Fork the repository
2. Create a new branch (`git checkout -b feature/improvement`)
3. Make your changes
4. Commit your changes (`git commit -am 'Add new feature'`)
5. Push to the branch (`git push origin feature/improvement`)
6. Create a Pull Request

## Testing

Run the test suite with:

```bash
npm test
```

## Future Improvements

- Add a score tracker
- Implement AI opponent
- Add sound effects
- Add animations for winning combinations
- Add multiplayer support
- Add customizable board sizes

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Inspired by the React official tutorial
- Thanks to the React team for Create React App
