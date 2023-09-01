# m6Day13ClassChallenge

# Catch Me Web Application

This is a simple web application that allows users to interact with a box by moving it using the mouse hover or pressing keys on the keyboard.

## Table of Contents

- [Demo](#demo)
- [Screenshots](#screenshots)
- [Features](#features)
- [How it Works](#how-it-works)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Author](#author)

## Demo

You can try out the live demo of the Catch Me web application [here](https://22pankajsahu.github.io/m6Day13ClassChallenge/).

## Screenshots

Included relevant screenshots of the application here.

![image](https://github.com/22pankajsahu/m6Day13ClassChallenge/assets/135128502/bfc0339f-92d4-4e76-928f-8aa7205852f7)

![image](https://github.com/22pankajsahu/m6Day13ClassChallenge/assets/135128502/2b2d5b7c-325f-47f4-9199-2a235215ebb9)


## Features

- Move the box by hovering your mouse over it.
- Move the box by pressing arrow keys on your keyboard.
- The box stays within the boundaries of the viewport.
- The box changes its position randomly when hovered or key pressed.

## How it Works

The Catch Me web application is built using HTML, CSS, and JavaScript. Here's a brief overview of how each component contributes to the functionality:

### HTML (index.html)

- The HTML file sets up the basic structure of the web page.
- It includes the box element (`<div id="box">`) that represents the movable element.
- Meta tags provide information about the author, keywords, and description of the web application.

### CSS (style tag)

- The CSS file provides styles for the box and ensures it stays within the viewport.
- The `body` is styled to have no margin and hide overflow.
- The `#box` element is styled with a background color, cursor pointer, and text properties.

### JavaScript (script tag)

- The JavaScript file provides the interactivity and functionality of the Catch Me application.
- It calculates the viewport dimensions and listens for mouseover and keypress events.
- When the mouse hovers over the box, it generates a random position for the box within the viewport.
- When arrow keys are pressed, it moves the box in the corresponding direction, ensuring it stays within the viewport boundaries.

## Installation

To run the Catch Me web application locally, follow these steps:

1. Clone this repository: `git clone https://github.com/22pankajsahu/m6Day13ClassChallenge.git`
2. Navigate to the project directory: `cd your-repo`
3. Open `index.html` in your web browser.

## Usage

1. Open the Catch Me web application in your web browser by following the installation instructions.
2. Hover your mouse over the box to see it move randomly within the viewport.
3. Use the arrow keys on your keyboard to control the box's movement (up, down, left, right).

## Contributing

Contributions are welcome! Here's how you can contribute:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature/new-feature`
3. Make your changes and commit: `git commit -m "Add new feature"`
4. Push to the branch: `git push origin feature/new-feature`
5. Submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Author

- Name: [PANKAJ SAHU](https://linkedin.com/in/22pankajsahu-)
- Email: [22pankajsahu@gmail.com](mailto:22pankajsahu@gmail.com)
- GitHub: [22pankajsahu](https://github.com/22pankajsahu)
