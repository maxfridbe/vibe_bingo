# Vibe Bingo

A vibecoded, dynamic, and printable bingo board generator. Create custom bingo boards directly in your browser, share them with others, or print them for your next event.

Test the site out here: [https://maxfridbe.github.io/vibe_bingo/](https://maxfridbe.github.io/vibe_bingo/)

## Features

- **Customizable Grid**: Set your bingo board size from 3x3 up to 10x10.
- **Dynamic Headers**: Personalize the top row with any text (default is "BINGO").
- **Editable Cells**: Click any cell to add your own text. Text automatically scales to fit the cell size.
- **Center Free Space**: Toggle an optional "FREE SPACE" in the center of the board (for odd-numbered grid sizes).
- **Persistent Storage**: Your board configuration and cell content are automatically saved to your browser's local storage.
- **Shareable Links**: Generate a unique URL that encodes your entire board setup, allowing you to share your custom bingo game with anyone.
- **Print Ready**: Includes a dedicated print mode that optimizes the board layout for paper.
- **Responsive Design**: Works on both desktop and mobile devices.

## How to Use

1.  **Configure**: Use the controls at the top to set your desired grid size and header text.
2.  **Edit**: Click on any cell in the grid and start typing to fill in your bingo items.
3.  **Save/Share**: Click "Share Link" to copy a URL to your clipboard that you can send to others.
4.  **Print**: Click "Print" to open your browser's print dialog and create physical copies of your board.
5.  **Reset**: Use the "Reset" button if you want to clear all contents and start from scratch.

## Tech Stack

- HTML5
- CSS3 (Tailwind CSS for styling)
- JavaScript (Vanilla)
- LocalStorage for persistence
- Base64 encoding for shareable URLs
