# SonicCloud

**SonicCloud** is an interactive audio-reactive artwork by [Reiniscouple](https://twitter.com/reiniscouple), coded in p5.js.  
It creates a dense, dynamic cloud of floating points that react in real-time to the external sounds captured through the user's microphone.

- **Visual Style**: A black canvas hosts a cloud of thousands of tiny white points centered on the screen. These points shift position, density, and color based on ambient audio frequencies.
- **Interaction**:
  - **Low frequencies (bass)** make the points group closer and turn green.
  - **High frequencies (treble)** make the points spread and turn blue.
  - The louder the sound, the larger the visual expansion.
- **Adaptive Design**: It scales dynamically to any screen size, from mobile to desktop.

## Preview

![SonicCloud Preview](./cover.jpg)

> *Open the artwork in a sound-rich environment for a more immersive experience.*

## Usage

This artwork uses the p5.js library. To run it locally:

1. Clone this repo
2. Open `index.html` in a modern browser
3. Click **"Ativar Microfone"** to start the interaction

## Mobile Support

Works on mobile browsers. Due to browser security, microphone access only begins after tapping the **activation button**.

## Licensing

This project is open for artistic appreciation and personal use. For commercial usage or exhibitions, please contact the artists.

---

Created by [Reiniscouple](https://twitter.com/reiniscouple)  
Built with [p5.js](https://p5js.org/)
