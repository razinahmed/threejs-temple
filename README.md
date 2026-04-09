# Three.js Temple

![Three.js](https://img.shields.io/badge/Three.js-3D-black)
![WebGL](https://img.shields.io/badge/WebGL-Graphics-red)
![License](https://img.shields.io/badge/License-MIT-green)

An interactive 3D visualization of a traditional Kerala temple built with Three.js. This project renders temple architecture in the browser using WebGL, featuring realistic lighting, camera controls, and a culturally accurate design.

## Features

- Real-time 3D rendering of Kerala temple architecture
- Interactive camera controls (orbit, zoom, pan)
- Ambient and directional lighting for realistic appearance
- Dark-themed environment with accent lighting
- Responsive canvas that adapts to viewport size
- No plugins required -- runs in any modern browser

## Tech Stack

| Technology | Purpose                    |
|------------|----------------------------|
| Three.js   | 3D rendering engine        |
| WebGL      | Hardware-accelerated graphics |
| JavaScript | Application logic          |
| CSS3       | Theming and layout         |
| Make       | Build automation           |

## Quick Start

1. Clone the repository:

```bash
git clone https://github.com/razinahmed/threejs-temple.git
cd threejs-temple
```

2. Serve the project locally:

```bash
npx serve .
```

3. Open your browser and navigate to `http://localhost:3000`.

## Theme

The visualization uses a dark base theme:

```css
--primary: #00d4aa;    /* Accent lighting color */
--background: #1e1e2e; /* Scene background */
```

## Build

```bash
make build
make test
```

## Project Structure

```
threejs-temple/
  styles/
    theme.css       # Visual theme
  Makefile          # Build commands
  LICENSE           # MIT License
```

## Contributing

Contributions are welcome, especially improvements to temple geometry, textures, and lighting accuracy.

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.
