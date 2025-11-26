🧠 Emoji Memory Game

Overview

This is a classic "Concentration" or "Pairs" game implemented using standard web technologies. The goal is to match all pairs of hidden emoji cards in the shortest amount of time. It features a simple, clean interface with a distinctive green and teal color theme.

🖼️ Image Section (UI Preview)

Here is a visual representation of the game interface:

✨ Features

Classic Gameplay: Standard match-the-pairs logic.

Emoji Cards: Uses a set of popular emojis for a fun, expressive feel.

Responsive Design: Styled to be playable across different screen sizes (although primarily focused on a desktop view in the current CSS).

Reset Functionality: A dedicated button to instantly shuffle the cards and start a new game.

Winning Notification: Alerts the player with a friendly message upon successful completion.

▶️ How to Play

Start: The game board is initialized with 16 cards (8 unique pairs) face-down.

Turn: Click on any card to flip it over and reveal the emoji.

Second Card: Click on a second card.

Match:

If the two revealed cards have the same emoji, they will stay face-up and are considered a match (boxMatch).

If the two revealed cards do not have the same emoji, they will automatically flip back down after a brief delay.

Win: The game is won when all 16 cards have been matched (all pairs are face-up).

💻 Technologies Used

HTML5: Structure of the game.

CSS3: Custom styling for layout, colors (#0a3c2f background and #0d614b container), card flipping animations, and general aesthetics.

Vanilla JavaScript: Game logic, shuffling, card flipping, match checking, and winning condition.

🚀 Setup and Installation

Since this project is built entirely with front-end code (HTML, CSS, and JS), it does not require any build tools or server setup.

Clone the repository (or download the files):

# Assuming you have a git repository
git clone [your-repo-link]
cd emoji-memory-game


Run the game: Open the index.html file directly in any modern web browser.

open index.html
