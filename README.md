Advanced Tic-Tac-Toe

A modern, animated Tic-Tac-Toe game with a unique twist: each player can only have three marks on the board at a time. Built with HTML, CSS, and JavaScript, this game features a sleek UI, animations, and accessibility support.

Features:

Unique Gameplay: Players are limited to three marks on the board. Placing a fourth mark removes the oldest one with a smooth animation.
Responsive Design: Adapts to various screen sizes, including mobile devices.
Animations: Marks fade in with scaling and rotation effects; oldest marks blur and fade out when removed.
Score Tracking: Keeps track of wins for each player (X and O).
Modal System: Displays game outcomes (win/draw) and game rules in accessible modals.
Accessibility: Includes ARIA attributes, keyboard navigation (ESC to close modals), and focus management.
Rules Modal: A dedicated button to view game rules, with a clean and modern presentation.

How to Play:

Players take turns placing their mark (X or O) on the 3x3 grid.
Each player can have only three marks on the board at a time.
Placing a fourth mark removes the oldest mark of that player with an animation.
The first player to align three marks horizontally, vertically, or diagonally wins.
If all cells are filled without a winner, the game ends in a draw.
Use the "Continue" button to reset the board and keep playing, or "Restart" to reset scores and the board.
Click the "Rules" button (top-right) to view the game rules at any time.

Installation:

Clone the repository:git clone https://github.com/your-username/advanced-tic-tac-toe.git


Open index.html in a web browser to play the game. No additional setup or dependencies are required.

File Structure:

index.html: The main file containing the HTML structure, CSS styles, and JavaScript logic for the game.

Technologies Used:

HTML5: For the game structure.
CSS3: For styling, animations, and responsive design (uses CSS Grid, Flexbox, and transitions).
JavaScript: For game logic, event handling, and DOM manipulation.
No external dependencies: Pure vanilla JavaScript and CSS.

Accessibility Features:

ARIA attributes for modals (role, aria-modal, aria-labelledby, etc.).
Keyboard support: Press Escape to close modals.
Focus management for modals and buttons.
High-contrast colors and clear visual feedback for better usability.


![Image](https://github.com/user-attachments/assets/def08391-a2da-48d4-ae44-f475a11aa27b)


Contributing:
Contributions are welcome! Please follow these steps:

Fork the repository.

Create a new branch (git checkout -b feature/your-feature).

Make your changes and commit (git commit -m "Add your feature").

Push to the branch (git push origin feature/your-feature).

Open a Pull Request.

Contact
For questions or feedback, feel free to open an issue on GitHub or contact 'arunparthi8686@gmail.com'.
