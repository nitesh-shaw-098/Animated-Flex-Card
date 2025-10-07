# 🌟 Animated Flex Cards with Particle Background

This project showcases a set of visually engaging, interactive flex cards. It features a stunning particle animation background, dynamic content generation for both images and text, and a stylish, animated gradient heading.

---

## 🚀 Live Demo

This project is live and interactive on CodePen. Click the link below to see it in action! The cards expand on click, and the background particles react to your mouse movements.

**[Click Here for the Live Demo](https://codepen.io/your-username/pen/your-pen-id)**


---

## ✨ Features

- **Interactive Flex Cards:** Cards smoothly expand when selected to reveal more information.
- **Particle.js Background:** An interactive particle animation in the background that responds to mouse hover effects.
- **Random Image Generation:** Each card dynamically fetches a random, high-quality image from an online service (`picsum.photos`) on page load.
- **Random Text Generation:** Card titles and descriptions are randomly selected from a predefined content pool, ensuring a unique look every time.
- **Fancy Animated Heading:** A stylish heading with a flowing gradient text effect.
- **Responsive Design:** The layout is fluid and works well on different screen sizes.
- **Pure JavaScript:** Built with vanilla JavaScript, requiring no external frameworks.

---

## 🛠️ Technologies Used

-   **HTML5**
-   **CSS3** (Flexbox, Animations, Custom Properties)
-   **JavaScript (ES6)**
-   **[particles.js](https://github.com/VincentGarreau/particles.js/)** for the background animation.

---

## 🔧 Setup and Usage

To run this project on your local machine, follow these simple steps.

**Prerequisites:**
- A modern web browser (e.g., Google Chrome, Firefox).
- A code editor, preferably **Visual Studio Code**.

**Installation:**
1.  Clone the repository or download the project files.
2.  Open the project folder in Visual Studio Code.

**Running the Project:**
This project must be run on a local server to allow the random image generation from the internet to work correctly. The easiest way to do this is with the **Live Server** extension in VS Code.

1.  **Install Live Server:** If you don't have it, go to the Extensions view (`Ctrl+Shift+X`) in VS Code, search for `Live Server`, and install it.
2.  **Start the Server:** Right-click on the `index.html` file and select **"Open with Live Server"**.
3.  Your browser will automatically open with the project running. Enjoy!

---

## 🎨 Customization

You can easily customize the content of the cards:

1.  Open the `index.html` file.
2.  Navigate to the `<script>` tag at the bottom.
3.  Modify the `randomTitles` and `randomDescriptions` arrays to change the text content that appears on the cards.

```javascript
const randomTitles = [
    "New Title 1", "New Title 2", "New Title 3", "New Title 4",
];

const randomDescriptions = [
    "Your custom description for the first card.",
    "Another description for the second card.",
    "And so on for the rest of the cards.",
    "The possibilities are endless.",
];
