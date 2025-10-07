# rating-ui

A tiny, accessible React rating component demo built with Vite.

This repository contains a small UI demo showing a star-based Rating component, plus supporting components (`Star`, `Button`, `Modal`) used by the demo app.

## Demo

Start the development server and open the app in your browser (by default Vite serves at http://localhost:5173):

1. Install dependencies

```bash
npm install
```

2. Start the dev server

```bash
npm run dev
```

Open http://localhost:5173 in your browser. The demo shows the interactive rating UI where you can hover and click stars to pick a rating and submit it via the UI.

## What you'll find

- `src/components/Rating.jsx` — main interactive rating component that renders stars and manages selection.
- `src/components/Star.jsx` — the presentational star icon used by `Rating`.
- `src/components/Modal.jsx` — a simple modal used in the demo.
- `src/components/Button.jsx` — small button component used across the demo.
- `src/App.jsx`, `src/main.jsx` — app bootstrap and demo wiring.

Refer to the component files for the full implementation and any additional props.

## Development notes

- This project uses Vite + React. The relevant scripts are in `package.json`:

  - `dev` starts the Vite dev server
  - `build` creates a production build
  - `preview` serves the production build locally

- Formatting / linting: none enforced by default. Add ESLint / Prettier if you want stricter checks.

## Build & preview

```bash
npm run build
npm run preview
```

## License

MIT
