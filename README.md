# Mini Drum Kit

A simple and interactive drum kit website built using JavaScript, HTML, and CSS. Users can play different drum sounds by either clicking on the corresponding drum images or by pressing designated keys on their keyboard.

## Features

- Play different drum sounds such as **Crash**, **Kick**, **Tom1**, **Tom2**, **Tom3**, **Tom4**, and **Snare**.
- Sounds can be triggered by clicking on the drum icons or by pressing keys.
- Uses `addEventListener` for both mouse clicks and keypress events.

## Demo

A live demo of the project can be found [https://mini-drum-kit-js.netlify.app/](https://mini-drum-kit-js.netlify.app/)


## Demo Video

Watch the demo of the mini drum kit in action:

[![Mini Drum Kit Demo]](./demo/mini-drum-kit.mp3)

## Technologies Used

- **HTML**: For the basic structure of the website.
- **CSS**: For styling the drum kit and creating a visually appealing user interface.
- **JavaScript**: Used to handle the functionality, including playing sounds and handling user input.

## How It Works

1. **User Input**:
   - Clicking on a drum button triggers the respective sound.
   - Pressing a corresponding key on the keyboard also triggers the drum sound.
   
2. **JavaScript Functions**:
   - `addEventListener('click', function)` to handle mouse clicks on the drum images.
   - `addEventListener('keypress', function)` to handle keyboard input and play the respective drum sound.
   
3. **Sound Files**:
   - Each drum sound is linked to an audio file, which is played when triggered.

