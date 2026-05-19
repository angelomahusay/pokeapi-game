# Who's That Pokémon?

A highly polished, interactive "Who's That Pokémon?" web application inspired by the classic cartoon bumpers. Guess the silhouetted Pokémon from multiple choices to maintain your highest streak!

## ✨ Features
- **Dynamic API Integration**: Fetches random Pokémon artwork and decoy names using the [PokéAPI](https://pokeapi.co/).
- **Modern UI/UX**: Built with Tailwind CSS, featuring glassmorphism, responsive single-card design, and smooth animations.
- **Score Tracking**: Persistent LocalStorage tracking for your 'Current Streak' and 'Best Streak'.
- **Keyboard Support**: Play the entire game without a mouse! Use keys `1`, `2`, `3`, and `4` to pick answers, and `Enter` or `Space` to play again.
- **Single-File App**: The entire game runs out of one HTML file without complex build tools.

## 🛠️ Tech Stack
- **HTML5** & **Vanilla JavaScript** (ES6+)
- **Tailwind CSS** (via CDN)
- **Google Fonts** (Poppins)
- **PokéAPI** (`https://pokeapi.co/`)

## 🚀 Installation & Setup

Since this application is a strictly single-file architecture without any build steps or local dependencies, setup is incredibly straightforward.

1. **Clone or Download** the repository to your local machine:
   ```bash
   git clone <your-repository-url>
   cd pokeapi-game
   ```
2. **Run the Application**:
   - **Easiest**: Simply double-click on the `index.html` file to open it in your default web browser.
   - **Recommended**: Use a local server like [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) in VS Code or [Five Server](https://marketplace.visualstudio.com/items?itemName=yandeu.five-server) for a better development experience. 

## 🎮 How to Play

1. When the app loads, you will see a solid black silhouette of a random Pokémon.
2. Read the 4 multiple-choice options provided below the image.
3. Make your guess by **clicking** the button or pressing the corresponding **number key (`1-4`)** on your keyboard.
4. If correct, the Pokémon is revealed in a green success state, and your streak goes up.
5. If incorrect, the correct answer is highlighted in green, your selection turns red, and your streak resets to 0.
6. Click **Play Again** or press **Enter / Space** to fetch a new challenge!

## 📜 Credits
- **Designed & Developed by**: Angelo M. Mahusay
- **Powered by**: [PokéAPI](https://pokeapi.co/)
