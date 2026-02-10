# 🎨 DrawMate

A simple and fun drawing app built with vanilla JavaScript, HTML, and CSS. DrawMate lets you unleash your creativity right in your browser with a clean, minimalist interface.

## 📦 Technologies

- `HTML5 Canvas`
- `Vanilla JavaScript`
- `CSS3`

## 🦄 Features

Here's what you can do with DrawMate:

- **Pick Your Color**: Choose any color from the stroke color picker to make your drawings pop.
- **Adjust Line Width**: Control how thick or thin your strokes are with the line width input.
- **Draw Freely**: Click and drag on the canvas to draw whatever comes to mind.
- **Clear Canvas**: Made a mistake? Hit the clear button and start fresh.

It's simple, straightforward, and perfect for quick sketches and doodles!

## 👩🏽‍🍳 The Process

I started by setting up an HTML5 canvas element, which is the foundation for all the drawing magic. Then I connected it to JavaScript to handle the drawing logic.

The first challenge was getting the mouse events to work properly. I had to track when the user presses down, moves, and releases the mouse to create smooth drawing strokes.

Next, I added controls for customizing the drawing experience - a color picker for changing stroke colors and a number input for adjusting line width. These give users creative control over their artwork.

The clear button was essential because everyone makes mistakes! It uses `clearRect()` to wipe the canvas clean.

I styled everything with CSS to create a clean, modern interface with a dark sidebar and a gradient logo that makes DrawMate feel polished and professional.

## 📚 What I Learned

During this project, I picked up some valuable skills working with the Canvas API and event handling:

### 🎨 Canvas API:
- **Drawing Context**: I learned how to get the 2D rendering context and use methods like `lineTo()`, `stroke()`, and `clearRect()`.
- **Line Properties**: Understanding `lineWidth`, `strokeStyle`, and `lineCap` helped me create smooth, customizable strokes.

### 🖱️ Mouse Event Handling:
- **Event Listeners**: I got comfortable with `mousedown`, `mouseup`, and `mousemove` events to track drawing actions.
- **Coordinates**: Calculating the correct position on the canvas using `clientX`, `clientY`, and canvas offsets was crucial for accurate drawing.

### 🎯 State Management:
- **Drawing State**: I learned to manage the `isPainting` boolean to control when the user is actively drawing versus just moving the mouse.

### 🐛 Debugging:
- **Finding Typos**: This project taught me the importance of careful code review. I fixed several typos that were breaking functionality (like `stokeStyle` instead of `strokeStyle`).

## 💭 How can it be improved?

- Add more drawing tools like shapes (circles, rectangles, triangles).
- Implement an eraser tool to selectively remove parts of drawings.
- Add undo/redo functionality to fix mistakes without clearing everything.
- Create a save feature to export drawings as images.
- Make it responsive for mobile devices with touch support.
- Add different brush styles like spray paint, pencil, or marker effects.
- Implement layers for more complex drawings.

## 🚦 Running the Project

To run the project in your local environment, follow these steps:

1. Clone the repository to your local machine.
2. Open `index.html` in your web browser.
3. Start drawing!

No build process, no dependencies - just pure vanilla JavaScript! 🍦

## 🎯 Quick Start

```bash
# Clone the repo
git clone https://github.com/yourusername/drawmate.git

# Navigate to the project
cd drawmate

# Open in your browser
open index.html
```

## 💡 Tips

- Start with a smaller line width (3-5) for detailed work
- Try different colors to make your drawings more vibrant
- Use thicker lines (10-20) for bold strokes and filling areas
- Don't be afraid to hit clear and start over - practice makes perfect!

---

Made with 💙 and lots of ~~coffee~~ creative energy!
