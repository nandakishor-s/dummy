# React Login Page

[![React](https://img.shields.io/badge/React-18-61DAFB?logo=react&logoColor=white)](https://reactjs.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

A clean, responsive, and accessible login page built with React featuring modern UI/UX best practices.

---

## Table of Contents

- [Features](#features)
- [Demo](#demo)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Customization](#customization)
- [Technologies](#technologies)
- [Contributing](#contributing)
- [License](#license)

---

## Features

| Feature | Description |
|---------|-------------|
| **Email & Password Validation** | Real-time client-side validation with helpful, user-friendly error messages |
| **Show/Hide Password Toggle** | Eye icon allows users to reveal or hide their password |
| **Remember Me** | Checkbox option to persist login state |
| **Forgot Password** | Quick access link for password recovery flow |
| **Loading State** | Simulated async login with an elegant submit spinner |
| **Success Feedback** | Green banner confirmation on successful login |
| **Responsive Design** | Fluid layout that looks great on mobile, tablet, and desktop |
| **Smooth Animations** | Card slide-up entrance and interactive button hover/focus states |
| **Accessibility** | Semantic HTML, proper ARIA labels, and keyboard navigation support |

---

## Demo

The login page features a modern card layout centered on a purple gradient background, with inline SVG icons for email and password fields.

![Login Page Preview](https://via.placeholder.com/800x500/667eea/ffffff?text=Login+Page+Preview)

> Replace the placeholder above with an actual screenshot of your app.

---

## Getting Started

### Prerequisites

| Requirement | Version |
|-------------|---------|
| [Node.js](https://nodejs.org/) | v16 or later |
| npm | Comes with Node.js |

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

The optimized output will be in the `build/` folder, ready for deployment.

### Running Tests

```bash
npm test
```

---

## Project Structure

```
react-login-page/
├── public/
│   └── index.html            # HTML template
├── src/
│   ├── components/
│   │   ├── LoginPage.js      # Main login page component
│   │   └── LoginPage.css     # Login page styles
│   ├── App.js                # Root component
│   └── index.js              # Application entry point
├── package.json              # Dependencies and scripts
└── README.md                 # Project documentation
```

---

## Customization

### Theming

You can easily customize the look and feel by modifying the CSS custom properties in `LoginPage.css`:

```css
:root {
  --primary-color: #667eea;
  --primary-hover: #5a6fd6;
  --error-color: #e74c3c;
  --success-color: #27ae60;
  --text-color: #333;
  --border-radius: 8px;
}
```

### Form Behavior

To connect the login form to your backend API, modify the `handleSubmit` function in `LoginPage.js`:

```javascript
const handleSubmit = async (e) => {
  e.preventDefault();
  // Replace with your API call
  const response = await fetch('/api/login', {
    method: 'POST',
    headers: { 'Content-Type': 'application/json' },
    body: JSON.stringify({ email, password }),
  });
  // Handle response...
};
```

---

## Technologies

| Technology | Purpose |
|------------|---------|
| **React 18** | UI component library |
| **CSS3** | Styling (custom properties, flexbox, gradients, animations) |
| **Create React App** | Project scaffolding and build tooling |

---

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

---

<p align="center">
  Made with ❤️ using React
</p>
