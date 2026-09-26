# Orbit Studio

An interactive 3D landing page concept by [Muzaffar Normurodov](https://github.com/MuzaffarJr). It demonstrates visual direction, responsive layout, CSS 3D composition, and practical interaction design in one self-contained page.

## Features

- Orbital hero rendered with CSS gradients, transforms, perspective and layered rings
- Pointer-responsive tilt on desktop, with a static fallback for reduced-motion preferences
- Responsive mobile navigation, keyboard focus states and a skip link
- Clear concept labeling: the directions shown are not client work
- No framework, package installation, API keys or external assets required

## Run locally

Open `index.html` in a modern browser. For a local server:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Decisions

The hero uses CSS 3D instead of WebGL so it loads without a 3D library and remains usable on modest devices. Pointer motion is optional. Navigation and content work without JavaScript; JavaScript adds menu behavior and pointer tilt.

## Portfolio context

This is a fictional studio concept created to demonstrate product design and front-end implementation. It is not a live agency or a record of paid client projects.

## License

Copyright © 2026 Muzaffar Normurodov. All rights reserved.
