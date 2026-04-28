# Mohit Graphs - Equation Visualizer

A sleek, interactive web-based tool for visualizing mathematical equations in real-time. Built with HTML5 Canvas, Math.js, and Chart.js.

## Features

- **Real-time Graphing**: Input equations and see them plotted instantly
- **Multiple Equations**: Add and manage multiple equations with different colors
- **Interactive Controls**:
  - Pan and zoom with mouse/touch
  - Adjustable viewport bounds
  - Variable sliders for dynamic parameters
- **Math Keyboard**: Built-in keyboard for common mathematical symbols and functions
- **Themes**: Dark and light mode toggle
- **Save/Load**: Persist your equations locally
- **Export**: Save graphs as PNG or SVG files
- **Responsive Design**: Works on desktop and mobile devices
- **Animation**: Smooth drawing animations for new equations

## Supported Functions

Mohit Graphs supports a wide range of mathematical expressions using Math.js:

- Basic arithmetic: `+`, `-`, `*`, `/`, `^`
- Trigonometric: `sin()`, `cos()`, `tan()`
- Logarithmic: `log()`, `ln()`
- Roots: `sqrt()`, `cbrt()`
- Absolute value: `abs()`
- Constants: `pi`, `e`
- Variables: `x` and custom variables (controlled by sliders)

## How to Use

1. **Open the App**: Simply open `mathviz.html` in any modern web browser
2. **Add Equations**:
   - Type an equation in the input field (e.g., `sin(x)`, `x^2`, `a*sin(b*x)`)
   - Press Enter or click "Add Equation"
   - Use the math keyboard for special symbols
3. **Interact with the Graph**:
   - **Pan**: Click and drag to move around
   - **Zoom**: Mouse wheel or use zoom buttons
   - **Adjust Viewport**: Modify X/Y min/max values in the sidebar
4. **Variable Sliders**: If your equation contains variables (other than `x`), sliders will appear automatically
5. **Manage Equations**:
   - Click equation text to edit
   - Use eye icon to hide/show
   - Use X to delete
6. **Save/Load**: Use the buttons in the header to save your work
7. **Export**: Export your graph as PNG or SVG

## Examples

Try these equations:
- `sin(x)`
- `x^2 / 4`
- `cos(x) + sin(2*x)`
- `a * sin(b * x)` (adjust `a` and `b` with sliders)
- `sqrt(abs(x))`
- `tan(x) / x`

## Dependencies

- [Math.js](https://mathjs.org/) - Mathematical expression parsing and evaluation
- [Chart.js](https://www.chartjs.org/) - Canvas rendering (though not heavily used)
- Google Fonts: Space Mono and Syne

All dependencies are loaded via CDN, so no installation is required.

## Browser Support

Works in all modern browsers that support:
- HTML5 Canvas
- ES6 JavaScript
- CSS Custom Properties (CSS Variables)

## Local Development

Since this is a single HTML file, you can:
- Open directly in browser
- Serve with any static web server
- Edit the HTML/CSS/JS directly in the file

## License

This project is open source. Feel free to use, modify, and distribute.

## Credits

Built with ❤️ using vanilla JavaScript, HTML5, and CSS3.