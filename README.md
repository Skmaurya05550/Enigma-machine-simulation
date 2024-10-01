# Enigma Machine Simulator

This is a simple web-based **Enigma Machine Simulator** that allows users to encode and decode messages based on the original Enigma machine's encryption mechanism. It simulates the basic rotor and reflector process of encoding and decoding text.

## Features

- Encode or decode a message using the Enigma-like rotor system.
- Interactive user interface with the ability to switch between encode and decode modes.
- Designed with simplicity for educational and illustrative purposes.

## Demo

![Enigma Machine Simulator](./demo-image.png)

## How to Use

1. Enter the message you wish to encode or decode in the input box.
2. Select whether you want to **encode** or **decode** the message.
3. Click the "Submit" button to process your message.
4. The processed message will appear below the input field.

## How It Works

The simulator uses three rotors and a reflector to mimic the basic functionality of the Enigma machine. Each letter passes through three rotors, a reflector, and then goes back through the rotors in reverse. 

- **Rotor 1**: `EKMFLGDQVZNTOWYHXUSPAIBRCJ`
- **Rotor 2**: `AJDKSIRUXBLHWTMCQGZNPYFVOE`
- **Rotor 3**: `BDFHJLCPRTXVZNYEIWGAKMUSQO`
- **Reflector**: `YRUHQSLDPXNGOKMIEBFZCWVJAT`

## Technologies Used

- **HTML**: For the structure of the webpage.
- **CSS**: For styling and layout.
- **JavaScript**: For processing the encoding/decoding functionality.

## How to Run Locally

1. Clone this repository:
    ```bash
    git clone https://github.com/your-username/enigma-machine-simulator.git
    ```
2. Open the `index.html` file in any modern web browser to start the simulator.

## Screenshot

Here’s how the simulator looks:

![Screenshot of the Enigma Machine Simulator](./screenshot.png)

## License

This project is licensed under the MIT License. Feel free to fork and modify for your own use!

