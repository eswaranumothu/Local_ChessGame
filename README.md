# Local_ChessGame
A browser-based chess game built with HTML, CSS, and JavaScript, allowing two players to play locally on the same device. The game features an interactive chessboard with drag-and-drop piece movement, move validation, and check/checkmate detection. It's fully responsive and works across different screen sizes

# ACCESS THE GAME HERE
https://eswaranumothu.github.io/Local_ChessGame/

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Local Chess Game - Development Process</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            padding: 20px;
        }
        h1, h2 {
            color: #2d3e50;
        }
        .section {
            margin-bottom: 20px;
        }
        ul {
            list-style-type: disc;
            margin-left: 20px;
        }
        p {
            margin-bottom: 15px;
        }
    </style>

   <h1>Local Chess Game - Development Process</h1>

   <div class="section">
        <h2>Project Overview</h2>
        <p>
            The <strong>Local Chess Game</strong> is a browser-based chess game built using HTML, CSS, and JavaScript. It allows two players to play a game of chess on the same device. The objective was to create a fully functional chessboard with drag-and-drop piece movement, move validation, and detection of check and checkmate.
        </p>
    </div>

  <div class="section">
        <h2>Development Process</h2>
        
<h3>1. Designing the Chessboard (HTML Structure)</h3>
        <p>
            The first step was to create the structure of the chessboard using HTML. An 8x8 grid was created to represent the chessboard, and each square was assigned specific attributes to later be styled with CSS. The HTML structure was simple and clean to allow easy customization.
        </p>

   <h3>2. Styling the Chessboard (CSS)</h3>
        <p>
            After setting up the board's structure, CSS was used to style the chessboard. Each square alternated between dark and light shades to mimic a standard chessboard. I used flexible layout techniques like CSS Grid to ensure the board was responsive and adaptable to different screen sizes. The chess pieces were also styled using images or icons for easy recognition.
        </p>

   <h3>3. Implementing Game Logic (JavaScript)</h3>
        <p>
            JavaScript was used to bring the game to life with interactive features and game logic. Key aspects of the game logic included:
        </p>
        <ul>
            <li><strong>Piece Movement:</strong> Pieces were allowed to move based on their individual movement rules (e.g., pawns only moving forward, rooks moving in straight lines). I implemented a system to track and update the positions of pieces on the board.</li>
            <li><strong>Turn Management:</strong> I ensured players alternated turns, and I implemented a system to check if a move was valid before allowing it.</li>
            <li><strong>Move Validation:</strong> The game checks if each move follows the correct rules for each piece. For example, a pawn cannot move diagonally unless it is capturing another piece.</li>
            <li><strong>Game End Conditions:</strong> The game tracks if a player’s king is in check or checkmate, and displays appropriate messages when these situations occur.</li>
        </ul>

   <h3>4. Interactive Features</h3>
        <p>
            To make the game more interactive, I included the ability to click and drag pieces, or click to select and move them to a valid square. I also highlighted valid move squares to guide players and make the game more intuitive.
        </p>

   <h3>5. Responsiveness</h3>
        <p>
            Ensuring the game looked good on different devices was crucial. I used CSS media queries to adjust the layout and scale the chessboard appropriately for different screen sizes, such as mobile phones, tablets, and desktops.
        </p>

   <h3>6. Testing and Debugging</h3>
        <p>
            After the core features were implemented, I tested the game thoroughly to make sure all chess rules were respected. This included testing edge cases like en passant and castling (if those features were included). I also performed device testing to make sure the game functioned properly on multiple screen sizes.
        </p>

   <h3>7. User Interface (UI) Enhancements</h3>
        <p>
            I focused on making the user interface simple yet intuitive. This included providing visual feedback when a player selected a piece, highlighting valid move squares, and showing notifications for check or checkmate. These enhancements improved the overall user experience.
        </p>
    </div>

<div class="section">
        <h2>Conclusion</h2>
        <p>
            The <strong>Local Chess Game</strong> project was an exciting challenge that allowed me to apply my knowledge of HTML, CSS, and JavaScript. The final result is a fully functional, responsive, and interactive chess game that provides an enjoyable experience for two players on the same device.
        </p>
    </div>


