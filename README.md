# ✨ Neon Aura AR

**Live:** [https://vansh-sainii.github.io/neon-aura-ar/](https://vansh-sainii.github.io/neon-aura-ar/)

Hands-in-camera **Neon Aura AR**: webcam skeleton, pinch effects, two-hand arcs, reactive audio. Built with **[MediaPipe Hands](https://developers.google.com/mediapipe/solutions/vision/hand_landmarker)** loaded from CDN.

This repo includes a **verbatim copy** of **[Axshatt/HandConnect](https://github.com/Axshatt/HandConnect)** as [`handconnect.html`](./handconnect.html) (same experience as [their GitHub Pages demo](https://axshatt.github.io/HandConnect/)). The default **[`index.html`](./index.html)** is the same app with small reliability fixes (camera/audio startup, error messages, theme clicks).

| Page | URL on your site |
|------|------------------|
| Recommended (patched) | […/index.html](https://vansh-sainii.github.io/neon-aura-ar/) |
| Original HandConnect file | […/handconnect.html](https://vansh-sainii.github.io/neon-aura-ar/handconnect.html) |

## Features

- 📷 **Live hand tracking** with neon skeleton and fingertip sparks
- 🎯 **Themes** — Rainbow, Cyberpunk, Lava, Ocean, Galaxy  
- ⚡ **Pinch** thumb + index → shockwave + zap sound  
- 🤲 **Two hands** — arcs between fingertips + hum when indexes get close  
- 🌐 **Hosted on GitHub Pages** — use **Enter experience** so the browser can unlock camera + audio

## Technologies

- HTML5 Canvas, Web Audio API, `getUserMedia`
- [MediaPipe Hands](https://developers.google.com/mediapipe/solutions/vision/hand_landmarker) (jsDelivr)

## Getting Started

1. Clone this repository:
   ```bash
   git clone https://github.com/Vansh-Sainii/neon-aura-ar.git
   ```

2. Open `index.html` — on **HTTPS** or **localhost** — then click **Enter experience** and **allow the camera**.

## Live Demo

Visit the live site: **[https://vansh-sainii.github.io/neon-aura-ar/](https://vansh-sainii.github.io/neon-aura-ar/)**

The same URL is in **`LIVE_SITE.txt`** at the repo root (plain text for easy copy-paste).

## Project Structure

```
neon-aura-ar/
├── index.html        # AR demo (HandConnect-based + reliability fixes)
├── handconnect.html  # Exact clone of Axshatt/HandConnect main branch
├── LIVE_SITE.txt     # Published Pages URL (one line)
├── LICENSE           # MIT License
└── README.md         # This file
```

## Contributing

Feel free to fork this project and submit pull requests for any improvements!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

**Made with ✨ by Vansh Saini**
