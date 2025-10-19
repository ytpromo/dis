# dis UI mockups

This repository now includes a lightweight frontend prototype so designers and developers can preview the landing page and dashboard layouts.

## Project structure

```
frontend/
├── dashboard.html   # Dashboard view with sidebar, metrics, and content panels
├── index.html       # Marketing landing page with hero, feature, and contact sections
└── styles.css       # Shared styling and layout tokens for both pages
```

## Getting started

No build tooling is required. You can open the HTML files directly in your browser or run a simple static server to preview with live reload.

### Prerequisites

- Node.js (optional, only if you want to run the development server command below)

### Install dependencies

There are no runtime dependencies for the static prototype. If you want to use a simple development server you can install `serve` globally:

```bash
npm install -g serve
```

### Run a development server

From the repository root run:

```bash
serve frontend
```

This will host the UI at `http://localhost:3000`. You can then navigate between `index.html` and `dashboard.html` using the links in the UI.

Alternatively, you can run:

```bash
npx http-server frontend
```

or any other static file server you prefer.

## Customization

- Update copy and illustrations in `frontend/index.html` to match current messaging.
- Adjust dashboard widgets in `frontend/dashboard.html` with live data once APIs are available.
- Modify shared colors, typography, and layout tokens in `frontend/styles.css`.
