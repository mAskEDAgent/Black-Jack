# 🃏 Web Blackjack

A lightweight, interactive web-based Blackjack game built from scratch using HTML, CSS, and JavaScript. This project allows users to start a round, draw new cards, and try to hit 21 without busting.

## ✨ Features

* **Accurate Card Values:** The game logic automatically evaluates face cards as 10 and Aces as 11.


* **Game State Protection:** The ability to draw a new card is locked once a player hits Blackjack or busts, preventing invalid game states.


* **Dynamic Interface:** The DOM updates in real-time to display the player's active hand, total sum, and current status messages (e.g., "You've got Blackjack!").


* **Casino Styling:** The UI is customized with a red table background image and bold goldenrod buttons to mimic a physical casino environment.



## 💻 Tech Stack

* **Frontend Core:** Vanilla JavaScript, HTML5, and CSS3.


* **Build Tool & Bundler:** Vite.



## 🚀 How to Run Locally

This project is configured to run using the Vite build tool.

1. Ensure you have Node.js installed on your machine.
2. Open your terminal inside the project folder.
3. Install the required dependencies:


```bash
npm install

```


4. Start the local development server:


```bash
npm run dev

```


(Note: You can also use `npm start` as it is mapped to the same Vite command).


5. Open the `localhost` URL provided in your terminal to play.
