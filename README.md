# Keyboard Key Detector ⌨️

## Description

Keyboard Key Detector is a simple web project built using **HTML, CSS, and JavaScript** that displays information about the key pressed by the user. Whenever a key is pressed, the application dynamically shows the **Key**, **Key Code**, and **Code** values in a table format.

This project helps beginners understand keyboard events, event handling, DOM manipulation, and dynamic content updates in JavaScript.

## Features

* Detects keyboard key presses in real time.
* Displays the pressed key.
* Shows the corresponding key code.
* Displays the keyboard event code.
* Updates data dynamically without refreshing the page.
* Clean and interactive user interface.

## Technologies Used

* **HTML** – For creating the webpage structure.
* **CSS** – For styling the layout and table.
* **JavaScript** – For handling keyboard events and updating the DOM dynamically.

## How It Works

1. The webpage waits for the user to press any key.
2. A `keydown` event listener detects the key press.
3. JavaScript captures:

   * Key (`e.key`)
   * Key Code (`e.keyCode`)
   * Code (`e.code`)
4. The captured information is displayed in a table on the webpage.


## Project Structure
Keyboard-Key-Detector/
│
├── index.html
├── style.css
└── script.js

## Example Output

| Key   | KeyCode | Code  |
| ----- | ------- | ----- |
| A     | 65      | KeyA  |
| Enter | 13      | Enter |
| Space | 32      | Space |

