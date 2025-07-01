# Hangman Game

A classic Hangman word guessing game built with React, TypeScript, and Vite. Players guess letters to reveal a hidden word before the hangman drawing is completed.

## 🎮 Features

- **Classic Gameplay**: Traditional hangman rules with 6 incorrect guesses allowed
- **Interactive Keyboard**: Click letters or use your physical keyboard to make guesses
- **Visual Feedback**: Dynamic hangman drawing that progresses with each wrong guess
- **Word Reveal**: Hidden word is revealed when the game ends
- **Game States**: Clear indication of win/loss conditions
- **Restart Functionality**: Press Enter to start a new game
- **Responsive Design**: Works on desktop and mobile devices
- **Large Word Dictionary**: 854 words to keep the game interesting

## 🚀 Getting Started

### Prerequisites

- Node.js (version 16 or higher)
- npm or yarn package manager

### Installation

1. Clone the repository:
```bash
git clone <your-repository-url>
cd Hangman
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open your browser and navigate to `http://localhost:5173`

### Building for Production

To create a production build:

```bash
npm run build
```

To preview the production build:

```bash
npm run preview
```

## 🎯 How to Play

1. **Start the Game**: The game begins with a randomly selected word
2. **Make Guesses**: Click on letter buttons or type on your keyboard
3. **Track Progress**: Watch the hangman drawing as you make incorrect guesses
4. **Win Condition**: Guess all letters in the word before 6 incorrect attempts
5. **Lose Condition**: Make 6 incorrect guesses (hangman drawing completes)
6. **New Game**: Press Enter to start a new game with a different word

## 🛠️ Technology Stack

- **React 19.1.0** - UI framework
- **TypeScript 5.8.3** - Type safety and development experience
- **Vite 6.3.5** - Fast build tool and development server
- **ESLint** - Code linting and formatting
- **CSS Modules** - Scoped styling

## 📁 Project Structure

```
Hangman/
├── src/
│   ├── App.tsx              # Main application component
│   ├── HangmanDrawing.tsx   # Visual hangman drawing component
│   ├── HangmanWord.tsx      # Word display component
│   ├── Keyboard.tsx         # Interactive keyboard component
│   ├── wordList.json        # Dictionary of 854 words
│   └── main.tsx             # Application entry point
├── public/                  # Static assets
├── package.json             # Dependencies and scripts
└── README.md               # This file
```

## 🎨 Key Components

- **App.tsx**: Main game logic, state management, and keyboard event handling
- **HangmanDrawing.tsx**: Renders the hangman figure based on incorrect guesses
- **HangmanWord.tsx**: Displays the word with guessed letters revealed
- **Keyboard.tsx**: Interactive keyboard with visual feedback for guessed letters

## 🎮 Game Logic

- **Word Selection**: Randomly selects from 854 words in the dictionary
- **Guess Tracking**: Maintains arrays of correct and incorrect guesses
- **Win/Loss Detection**: Checks for complete word guess or maximum incorrect attempts
- **Input Validation**: Only accepts single letter inputs (a-z)
- **Game Reset**: Clears state and selects new word on Enter key press

## 🚀 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint for code quality

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- Classic Hangman game concept
- React and TypeScript communities for excellent documentation
- Vite team for the fast build tool

---

**Enjoy playing Hangman!** 🎯
