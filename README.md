# ✨ Neon Aura AR

An interactive browser-based Augmented Reality (AR) experience that combines **real-time hand tracking**, **dynamic particle effects**, **gesture recognition**, and **reactive audio synthesis** to create an immersive cyberpunk-inspired visual experience.

Built entirely using **HTML5**, **JavaScript**, **MediaPipe Hands**, and the **Canvas API**, with no backend required.

---

## Demo

Open `index.html` in a modern browser and allow camera access.

> **Recommended Browser:** Google Chrome or Microsoft Edge (latest version)

---

## Features

### Real-Time Hand Tracking

* Detects up to **2 hands simultaneously**
* Tracks **21 landmarks per hand**
* Smooth real-time landmark rendering
* Live FPS counter

### Gesture Recognition

* Pinch detection
* Open hand detection
* Closed fist detection
* Hand spread estimation
* Gesture status display

### Interactive Visual Effects

* Neon glowing hand skeleton
* Rainbow fingertip particles
* Dynamic lightning between hands
* Animated shockwaves
* Physics-based particle system
* Rotating mandala effect
* Motion-responsive Matrix-style background

### Audio Effects

* Spatial humming effect
* Distance-based pitch modulation
* Pinch-triggered zap sound
* Web Audio API synthesis

### Themes

Switch between multiple visual themes:

* Rainbow
* Cyberpunk
* Lava
* Ocean
* Galaxy

---

## Technologies Used

* HTML5
* CSS3
* JavaScript (ES6)
* MediaPipe Hands
* HTML5 Canvas
* Web Audio API

---

## Project Structure

```
project/
│
├── index.html
└── README.md
```

The application is completely self-contained inside a single HTML file.

---

## How It Works

1. User grants webcam permission.
2. MediaPipe detects hand landmarks in real time.
3. Gesture recognition processes:

   * Pinch
   * Hand spread
   * Finger positions
4. Canvas renders:

   * Skeleton
   * Glow effects
   * Particles
   * Lightning
   * Ripples
5. Web Audio API generates reactive sound effects based on hand movement.

---

## Controls

| Action                   | Effect                                 |
| ------------------------ | -------------------------------------- |
| Move hands               | Generates particles and motion effects |
| Bring two hands together | Lightning effects                      |
| Pinch fingers            | Creates shockwave + zap sound          |
| Change theme             | Updates colors and visual style        |

---

## Requirements

* Webcam
* Camera permission
* Modern browser with:

  * WebGL support
  * Canvas support
  * Web Audio API support

---

## Performance

The application is optimized for real-time interaction by:

* Using `requestAnimationFrame()`
* Efficient Canvas rendering
* Lightweight particle physics
* MediaPipe GPU-accelerated hand tracking
* Minimal DOM updates

---

## Future Improvements

* Additional gesture recognition
* Finger drawing mode
* AR object interaction
* Hand-based menu controls
* Custom particle presets
* Recording and screenshot support
* Three.js integration
* Multiplayer synchronized AR

---

## Running the Project

Simply clone the repository and open the HTML file.

```bash
git clone https://github.com/yourusername/neon-aura-ar.git
cd neon-aura-ar
```

Open:

```
index.html
```

Alternatively, serve it using a local HTTP server:

```bash
python -m http.server
```

Then visit:

```
http://localhost:8000
```

---

## Browser Compatibility

| Browser | Supported |
| ------- | --------- |
| Chrome  | Yes       |
| Edge    | Yes       |
| Firefox | Partial   |
| Safari  | Partial   |

Chrome is recommended for the best MediaPipe and Web Audio compatibility.

---

## License

This project is open source and available under the MIT License.

---

## Acknowledgements

* Google MediaPipe
* HTML5 Canvas
* Web Audio API
* JavaScript Community
