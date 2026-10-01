# Chitro AI 2.0

A lightweight, multilingual AI image generator web application. Chitro AI enables users to enter text prompts in multiple languages (including Bengali and English) to generate images on demand, featuring built-in client-side prompt safety filters and immediate download capability.

## Features

- **Multilingual Prompt Handling**: Accepts prompts across languages for direct AI image rendering.
- **Client-Side Safety Checks**: Validates user inputs against a configurable blocklist before dispatching to generation endpoints.
- **Clean Responsive Interface**: Single-page Bootstrap layout with live preview, loading state overlays, and direct PNG download.
- **Zero Heavy Dependencies**: Runs directly in any modern browser without complex build tooling.

## Tech Stack

- **Frontend**: Vanilla JavaScript (ES6+ Fetch API), HTML5, Bootstrap 4.5, jQuery
- **Backend / Inference**: REST API endpoint hosted via Flask

## Getting Started

No build pipeline or package manager required.

1. **Clone the repository:**
   `ash
   git clone https://github.com/Neamul09/chitro-AI-2.0.git
   cd chitro-AI-2.0
   `

2. **Run locally:**
   Open `index.html` directly in your browser, or spin up a local development server:
   `ash
   # Using Python 3
   python -m http.server 8000

   # Or using Node
   npx serve .
   `
   Navigate to `http://localhost:8000`.

## Project Structure

`
chitro-AI-2.0/
├── index.html        # Main application layout, styles, and prompt-handling logic
├── replit.nix        # Environment config for Replit hosting
├── .replit           # Replit runner config
└── LICENSE           # MIT License
`

## License

Distributed under the [MIT License](LICENSE).