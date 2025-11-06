# Best Shop - Suitcase E-commerce

Multi-page responsive e-commerce website for suitcases.

## Prerequisites

- Node.js (v14 or higher)
- npm

## Installation

1. Clone the repository
2. Install dependencies:
```bash
npm install
```

## Running the Project

Start the development server:
```bash
npm run dev
```

This will:
- Compile SCSS to CSS
- Start lite-server on `http://localhost:3000`
- Open the website in your browser

## Development Commands

- `npm run compile` - Compile SCSS to CSS (one-time)
- `npm run watch:sass` - Watch SCSS files for changes
- `npm run serve` - Start lite-server
- `npm run dev` - Compile and serve
- `npm run dev:watch` - Compile, watch, and serve (recommended for development)

## Project Structure
```
fundamentals-project-template/
├── dist/              # Compiled CSS (auto-generated)
├── src/
│   ├── assets/        # JSON data
│   ├── html/          # Additional HTML pages
│   ├── js/            # JavaScript files
│   ├── scss/          # SASS stylesheets
│   └── index.html     # Homepage
├── bs-config.json     # BrowserSync configuration
├── package.json       # Dependencies
└── README.md
```

## Technologies Used

- HTML5
- SASS/SCSS
- Vanilla JavaScript (ES6+)
- BrowserSync (lite-server)

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)