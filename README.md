# 🎲 Tenzies

A React + Vite dice game where you roll until all dice show the same value. Hold dice to freeze them between rolls and race to match all ten. Features state management, conditional rendering, accessibility support, and a confetti celebration on win.

## ✨ Features

- Roll 10 dice and click to hold/freeze individual dice between rolls
- Win when all dice are held and show the same value
- Confetti celebration animation on victory
- Accessible UI with ARIA labels and screen reader announcements
- Simple, responsive layout styled in `index.css`
- Vite-powered dev setup

## 🚀 Getting Started

Install dependencies:
```
npm install
```

Run the dev server:
```
npm run dev
```

Build for production:
```
npm run build
```

Preview the production build:
```
npm run preview
```

## 🗂️ Project Structure

- `App.jsx`: main game logic, dice state, win condition, and roll/hold handlers
- `Die.jsx`: individual die button component with hold state styling
- `index.jsx`: React entry point
- `index.css`: global styles
- `vite.config.js`: Vite configuration

## 🎮 How to Play

1. Click **Roll** to roll all unheld dice
2. Click any die to **hold** it (turns green) — it won't change on the next roll
3. Keep rolling and holding until all 10 dice show the same number
4. Celebrate with confetti! Click **New Game** to play again

## 🛠️ Customization

- Adjust the number of dice or starting values in `App.jsx`
- Change the held die color in `Die.jsx`
- Tweak styles and layout in `index.css`

## 🧰 Tech Stack

- React
- Vite
- nanoid (unique ID generation)
- react-confetti (win celebration)
- CSS

## 🙌 Acknowledgements

Built as part of the [Scrimba React course](https://scrimba.com/learn-react-c0e).
