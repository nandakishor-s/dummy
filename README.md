# React Login Page

A clean, responsive login page built with React.

## Features

- **Email & password validation** — real-time client-side validation with helpful error messages
- **Show/hide password toggle** — eye icon lets users reveal their password
- **Remember me & Forgot password** — standard login form options
- **Loading spinner** — simulated async login with a submit spinner
- **Success feedback** — green banner on successful login
- **Responsive design** — looks great on mobile, tablet, and desktop
- **Smooth animations** — card slide-up entrance and interactive button states

## Screenshot

The login page features a modern card layout centered on a purple gradient background, with inline SVG icons for email and password fields.

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v16 or later recommended)
- npm (comes with Node.js)

### Installation

```bash
# Clone the repository
git clone <repo-url>
cd dummy

# Install dependencies
npm install
```

### Running the App

```bash
npm start
```

The app will open at [http://localhost:3000](http://localhost:3000).

### Building for Production

```bash
npm run build
```

The optimised output will be in the `build/` folder.

## Project Structure

```
├── public/
│   └── index.html          # HTML template
├── src/
│   ├── components/
│   │   ├── LoginPage.js    # Login page component
│   │   └── LoginPage.css   # Login page styles
│   ├── App.js              # Root component
│   └── index.js            # Entry point
├── package.json
└── README.md
```

## Technologies

- React 18
- CSS3 (custom properties, flexbox, gradients, animations)

## License

MIT
