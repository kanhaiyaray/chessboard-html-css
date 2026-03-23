# ♟ Chess Board

A simple static chess board built with plain HTML and CSS using float-based layout and HTML entities for chess pieces.

---

## 📁 File Structure
```
chess-board/
├── index.html     ← board structure with pieces
├── styles.css     ← board styling and layout
└── README.md      ← this file
```

---

## 🚀 Getting Started

No installation needed. Just open in a browser:
```bash
open index.html
```

---

## 🎨 CSS Overview

### Body
```css
background-color: rgb(6, 6, 119);  /* dark blue background */
color: white;
padding: 0;
margin: 0;
```

### Board Container
```css
.chess_board {
  height: 640px;
  width: 640px;
  margin: auto;   /* centers board on page */
}
```

### Squares
| Class | Color | Text Color | Usage |
|-------|-------|------------|-------|
| `.box1` | Black | White | Dark squares |
| `.box2` | White | Black | Light squares |

- Each square: **80×80px**, `float: left`
- Font size: `3.2rem` for piece symbols
- Text aligned to center

---

## ♟ Piece Reference (HTML Entities)

| Entity | Symbol | Piece |
|--------|--------|-------|
| `&#9812;` | ♔ | White King |
| `&#9813;` | ♕ | White Queen |
| `&#9814;` | ♖ | White Rook |
| `&#9815;` | ♗ | White Bishop |
| `&#9816;` | ♘ | White Knight |
| `&#9817;` | ♙ | White Pawn |
| `&#9818;` | ♚ | Black King |
| `&#9819;` | ♛ | Black Queen |
| `&#9820;` | ♜ | Black Rook |
| `&#9821;` | ♝ | Black Bishop |
| `&#9822;` | ♞ | Black Knight |
| `&#9823;` | ♟ | Black Pawn |

---

## 🏁 Board Layout (8 Rows)

| Row | Content |
|-----|---------|
| Row 1 | Black back rank pieces |
| Row 2 | Black mixed pieces |
| Row 3 | Empty squares |
| Row 4 | Empty squares |
| Row 5 | Empty squares |
| Row 6 | Empty squares |
| Row 7 | White back rank pieces |
| Row 8 | White mixed pieces |

---

## 🛠️ Built With

| Technology | Usage |
|------------|-------|
| HTML5 | Board structure, chess entities |
| CSS3 | Float layout, square styling |

---

## 📜 License

MIT — free to use and modify.
