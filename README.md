# vr-viewer

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

360度写真をドロップするとぐるぐる見渡せます

A simple, client-side 360° photo viewer. Drag and drop a JPEG file into your browser to view it in an immersive VR scene powered by A-Frame.

## Demo

- **[Live Demo](https://code4fukui.github.io/vr-viewer/)**

## Features

- **Drag & Drop:** Instantly load 360° JPEG images from your local machine.
- **VR Ready:** Built with A-Frame for immersive viewing on VR headsets and desktops.
- **Minimalist UI:** The viewer starts with a simple instruction, "Drop 360deg JPG File here," which is replaced by your image.
- **Client-Side Processing:** All file handling is done in the browser. No data is uploaded.

## Usage

1.  Open the [Live Demo](https://code4fukui.github.io/vr-viewer/).
2.  Drag a 360° JPEG file (with a `.jpg` extension) from your computer onto the browser window.
3.  The scene will immediately update to display your image on the `<a-sky>` background.

## Core Libraries

- [A-Frame](https://aframe.io/) (v1.2.0): The web framework for building virtual reality experiences.
- [waitDropFiles.js](https://js.sabae.cc/waitDropFiles.js): A utility for handling file drop events.
- [readAsDataURLAsync.js](https://js.sabae.cc/readAsDataURLAsync.js): A utility for reading local files as Data URLs.

## License

MIT License