# 🧠 Memory Game

A classic Memory Game built with vanilla HTML, CSS, and JavaScript. This project is a simple, client-side application that can be played by two players, designed to be fully functional on both desktop and mobile browsers.

## 🚀 Features

* **Two-Player Mode:** Play against a friend on the same device.
* **Dynamic Game Board:** The game automatically generates a 5x10 grid with 25 unique pairs of cards.
* **Responsive Design:** The layout adjusts to fit various screen sizes, from mobile phones to larger displays.
* **Touch-Optimized:** Includes specific handling for mobile touch events to prevent accidental zooming and improve the user experience.
* **Scoreboard:** Tracks and displays the scores for each player.
* **Game-Over Screen:** A clean, modal screen shows the winner or if it's a tie once all pairs are matched.

## 💻 Technologies Used

* **HTML5:** For the game's structure and content.
* **CSS3:** For styling, including a modern gradient background, responsive grids, and smooth animations for card flips and player turns.
* **JavaScript (ES6):** For all game logic, including:
    * Shuffling the cards.
    * Handling card flips and matching logic.
    * Managing player turns and scoring.
    * Resetting the game.

## 🕹️ How to Play

1.  Open the `index.html` file in your web browser.
2.  The game board will automatically load with 50 face-down cards.
3.  Player 1 starts. Click or tap on any two cards to flip them over.
4.  If the cards match, they will remain face-up, and Player 1 gets a point and another turn.
5.  If the cards do not match, they will flip back over after a short delay, and the turn passes to Player 2.
6.  The game ends when all pairs have been found. The winner is the player with the highest score.
7.  Click the **"Nuova Partita"** (New Game) button at any time to start a new game.

## 🤝 Contributing

This is a simple project for educational purposes. Feel free to fork the repository and experiment with new features, such as:

* Adding a timer to track game duration.
* Implementing different board sizes (e.g., 4x4, 6x6).
* Adding new card symbols or themes.
* Creating a single-player mode.

## 📄 License

This project is open-source and available under the [MIT License](https://opensource.org/licenses/MIT).