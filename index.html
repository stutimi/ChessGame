const board = document.getElementById("chessboard");

// Unicode symbols for chess pieces
const pieces = {
  black: {
    king: "♚",
    queen: "♛",
    rook: "♜",
    bishop: "♝",
    knight: "♞",
    pawn: "♟︎"
  },
  white: {
    king: "♔",
    queen: "♕",
    rook: "♖",
    bishop: "♗",
    knight: "♘",
    pawn: "♙"
  }
};

// Generate initial board state
const initialBoard = [
  ["♜", "♞", "♝", "♛", "♚", "♝", "♞", "♜"],
  ["♟︎", "♟︎", "♟︎", "♟︎", "♟︎", "♟︎", "♟︎", "♟︎"],
  ["", "", "", "", "", "", "", ""],
  ["", "", "", "", "", "", "", ""],
  ["", "", "", "", "", "", "", ""],
  ["", "", "", "", "", "", "", ""],
  ["♙", "♙", "♙", "♙", "♙", "♙", "♙", "♙"],
  ["♖", "♘", "♗", "♕", "♔", "♗", "♘", "♖"]
];

// Render board
function renderBoard() {
  board.innerHTML = "";
  for (let row = 0; row < 8; row++) {
    for (let col = 0; col < 8; col++) {
      const square = document.createElement("div");
      square.classList.add("square");
      square.classList.add((row + col) % 2 === 0 ? "white" : "black");
      square.dataset.row = row;
      square.dataset.col = col;

      const piece = initialBoard[row][col];
      if (piece) {
        const pieceEl = document.createElement("div");
        pieceEl.classList.add("piece");
        pieceEl.draggable = true;
        pieceEl.textContent = piece;
        square.appendChild(pieceEl);
      }

      board.appendChild(square);
    }
  }
}

// Drag and drop logic
let draggedPiece = null;

document.addEventListener("dragstart", function (e) {
  if (e.target.classList.contains("piece")) {
    draggedPiece = e.target;
  }
});

document.addEventListener("dragover", function (e) {
  e.preventDefault();
});

document.addEventListener("drop", function (e) {
  e.preventDefault();
  const target = e.target;

  // Allow drop only on squares
  if (target.classList.contains("square") && draggedPiece) {
    target.innerHTML = "";
    target.appendChild(draggedPiece);
    draggedPiece = null;
  }
});

renderBoard();
