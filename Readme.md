# 🎨 Color Switch

An interactive web app that changes a canvas's background colour when you click one of six coloured circles — built with plain HTML, CSS and JavaScript (no frameworks, no libraries).

Made by **Radhika Singh** as part of my personal JavaScript/DOM practice projects.

## 🔗 Live Demo
https://radhikasingh6627-bit.github.io/Color-Switch/

## 📸 Preview


v


































## ✨ Features

- Six clickable coloured circles (red, yellow, green, blue, peru, purple)
- Instant background colour change on click — no page reload
- Built entirely with vanilla JavaScript DOM event listeners

## 🛠️ Tech Stack

- **HTML5** – page structure
- **CSS3** – circle styling and layout
- **JavaScript (ES6)** – click event handling and DOM manipulation

## 📁 Project Structure

```
color-switch/
├── index.html      # Structure, styles, and logic (single file)
└── README.md        # This file
```

## 🚀 How to Run Locally

1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/color-switch.git
   cd color-switch
   ```
2. Open `index.html` directly in any modern web browser (double-click it, or right-click → Open with → Chrome/Edge).

No build step, no dependencies, no server required.

## 🧠 How It Works

- `document.querySelectorAll(".d")` selects all six circle elements.
- Each circle has a `click` event listener attached via `addEventListener`.
- On click, the listener sets `document.getElementById("canvas").style.backgroundColor` to the colour mapped to that circle.

## 🔮 Future Enhancements

- Add a custom colour picker input
- Add smooth CSS transition on colour change
- Make the layout responsive for mobile screens

## 👩‍💻 Author

**Radhika Singh**
B.Tech CSE (AI & ML), Shri Ramswaroop Memorial University

## 📄 License

This project is open source and available under the MIT License.
