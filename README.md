# Modal/ Popup

A simple UI component designed to provide important information (Response/Feedback/Alerts ect.) for an interactive user experience.

## Table of Contents
- [Project Overview](#project-overview)
- [Technologies Used](#technologies-used)
- [Features](#features)
- [Learnings](#learnings)
- [Challenges Faced](#challenges-faced)
- [Installation and Usage](#installation-and-usage)
- [Screenshots](#screenshots)
- [Acknowledgments](#acknowledgments)
- [Contact](#contact)

## Project Overview

The Modal/Popup App is designed to enhance user interactions by bringing important information or actions to the forefront without navigating away from the current page.This keeps users engaged and focused, while providing the necessary contextual information needed without cluttering the main page layout.
## Technologies Used

- HTML
- CSS
- JavaScript

## Features

- Reduce Clutter.
- Provides Progressive Discloser (providing additional information as needed to user).
- Feedback and Alerts.
- Aesthetics and Design.

## Learnings

During this project, I gained a deeper understanding of JavaScript fundamentals, including:
- DOM manipulation, functions and event listeners.
- Creating and updating HTML elements dynamically.
- CSS Styling (using Keyframe's).
- Incremental Complexity.
## Challenges Faced

One challenge I encountered was implementing  the ``openModal()`` function. I had to remember that when working with ``<form>`` elements, clicking the ``<button>`` triggers a browser refresh as a default behavior for a form submission. Using the ``e.preventDefault()`` method solved the issue allowing me to modify the display of the ``modal`` element to ``block`` making it visible on the screen.
```
function openModal(e) {
    e.preventDefault();
    modal.style.display = "block";
}
```
  

## Installation and Usage

1. Clone this repository: `git clone https://github.com/josephc1417/ModalPopUp.git`
2. Open `index.html` in your web browser.
3. Start adding and managing your tasks!

## Screenshots

![Screenshot 1](./Images/Screenshot%202023-08-11%20090626.png)
![Screenshot 2](./Images/Screenshot%202023-08-11%20090705.png)

## Acknowledgments

I want to thank ``Udemy-100 days of JavaScript`` for their tutorial on DOM manipulation, which helped me understand the core concepts.
Special thanks to ``Ewomazino Akpareva`` for providing feedback and suggestions during the development process.

## Contact

Feel free to reach out to me on LinkedIn for any questions or feedback.
