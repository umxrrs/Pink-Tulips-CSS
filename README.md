# Pink Tulips Animation

---

## Description
This project is a CSS-based animation of pink tulips with a dynamic, growing effect set against a night-themed background. The animation features three tulips with petals, stems, leaves, and glowing lights, accompanied by grass and other foliage elements that grow and move. The scene uses CSS animations and transformations to create a visually appealing, 3D-like effect without requiring external libraries or frameworks.

---

## Project Structure
- `index.html`: The main HTML file containing the structure of the animation.
- `styles.css`: Contains all CSS styles and animations for the tulips, grass, and background.
- `script.js`: A small JavaScript file to handle the initial loading animation by removing the `not-loaded` class after a delay.
  
---

## Setup Instructions
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/umxrrs/Pink-Tulips-CSS
   cd Pink-Tulips-CSS
   ```
2. **Open The Project**:
- Open `index.html` in a web browser to view the animation.
- Alternatively, use a local development server (e.g., with VS Code's Live Server extension or by running `python -m http.server` in the project directory) to serve the files.

---

## Usage
- The animation starts automatically after a 1-second delay when the page loads.
- No user interaction is required; the tulips, grass, and lights animate continuously.
- The animation is responsive and uses viewport units (`vmin`) for scaling, ensuring it adapts to different screen sizes.
  
---

##Customization
- **Colors**: Modify the `--dark-color`, `--c`, or other color values in `styles.css` to change the color scheme.
- **Animation Timing**: Adjust the animation durations and delays in `styles.css` (e.g., `--fl-speed`, `animation-delay`) to alter the speed or sequence of animations.
- **Scale and Position**: Tweak the `transform` properties or sizes (e.g., `width`, `height`) in `styles.css` to adjust the layout or scale of elements.
  
---

## Browser Compatibility
The animation uses modern CSS features like `transform`, `animation`, and `linear-gradient`. It is compatible with modern browsers (e.g., Chrome, Firefox, Edge, Safari). Ensure your browser is updated for the best experience

---

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your changes. Ensure that any modifications maintain the animation's visual integrity and performance

---

## Built By umxrrs
