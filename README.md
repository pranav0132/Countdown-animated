# Animated Countdown

This project demonstrates an animated countdown using HTML, CSS, and JavaScript. The animation displays a countdown from 3 to 0 and reveals a "GO" message at the end. The user can replay the countdown animation by clicking the "Replay" button.

## Project Overview

The project consists of:

- A countdown timer that starts from 3 and counts down to 0.
- The final "GO" message is shown when the countdown reaches zero.
- A "Replay" button allows the user to restart the countdown.
- Smooth animations for the countdown numbers and the final message.

## Files

- **index.html**: Contains the structure of the countdown and the replay button.
- **style.css**: Styles the layout, countdown animations, and the replay button.
- **script.js**: Contains the logic to handle the countdown animation and reset functionality.

## Getting Started

### Prerequisites

To run this project, all you need is a web browser.

### Installation

1. Clone this repository or download the project files.
2. Open the `index.html` file in any modern web browser.

### Usage

1. When the webpage loads, the countdown will start automatically.
2. Once the countdown reaches zero, the "GO" message will be displayed.
3. To restart the countdown, click the **Replay** button.

### Code Explanation

- **HTML (`index.html`)**:
    - The `div.counter` element contains the countdown numbers.
    - The `div.final` element displays the final "GO" message.
    - The `button#replay` allows the user to replay the countdown.

- **CSS (`style.css`)**:
    - Styles the layout and positions the countdown numbers and "GO" message at the center of the page.
    - Defines the keyframe animations for the countdown numbers (`goIn` and `goOut`).
    - The `#replay` button is styled for an interactive hover effect.

- **JavaScript (`script.js`)**:
    - Handles the countdown animation by adding and removing classes from each number.
    - When the countdown ends, the final message is displayed, and the replay button can be clicked to restart the countdown.

### Features

- **Smooth countdown animation**: Numbers rotate and transition in and out.
- **Replay functionality**: Clicking the replay button resets the countdown and runs the animation again.
- **Responsive design**: The countdown is centered and scales well for different screen sizes.

### License

This project is open-source and free to use.


- **Google Fonts**: 'Roboto' font is used for the text.
