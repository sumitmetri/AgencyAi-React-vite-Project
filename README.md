# Agency.ai — Digital Agency Website

A modern, responsive digital agency website built with React and Vite. Agency.ai showcases digital services, featured projects, trusted companies, team information, and a contact section in a clean, animated interface.

## 🌐 Live Demo

**Visit the website:** [https://agencyai-react-vite.netlify.app](https://agencyai-react-vite.netlify.app)

## ✨ Features

- **Responsive Design:** Adapts to desktop, tablet, and mobile screens.
- **Modern UI:** Clean layouts, typography, and reusable components.
- **Dark and Light Themes:** Switch between themes for a personalized viewing experience.
- **Animated Elements:** Smooth entrance and scroll-based animations.
- **Services Section:** Presents the digital agency's services.
- **Trusted By Section:** Displays company logos.
- **Our Work Section:** Showcases selected projects and portfolio items.
- **Team Section:** Introduces the agency's team.
- **Contact Section:** Provides a section for visitors to connect with the agency.
- **Mobile Navigation:** Includes a collapsible navigation menu for smaller screens.

## 🛠️ Tech Stack

- **React** — Component-based user interface development.
- **Vite** — Development server and production build tool.
- **Tailwind CSS** — Utility-first styling and responsive layouts.
- **Motion** — Animations and scroll-based visual effects.
- **ESLint** — Code quality and linting.

## 📁 Project Structure

```text
Agency-AI/
├── public/
│   ├── favicon.ico
│   └── icons.svg
├── src/
│   ├── assets/                 # Images, logos, and icons
│   │   └── assets.js           # Asset exports
│   ├── components/
│   │   ├── ContactUs.jsx       # Contact section
│   │   ├── Hero.jsx            # Hero section
│   │   ├── Navbar.jsx          # Navigation bar
│   │   ├── OurWork.jsx         # Portfolio section
│   │   ├── ServiceCard.jsx     # Reusable service card
│   │   ├── Services.jsx        # Services section
│   │   ├── Teams.jsx           # Team section
│   │   ├── ThemeToggleBtn.jsx  # Theme switcher
│   │   ├── Title.jsx           # Reusable section title
│   │   └── TrustedBy.jsx       # Company logos
│   ├── App.jsx                 # Main application component
│   ├── index.css               # Global styles and Tailwind CSS
│   └── main.jsx                # Application entry point
├── index.html
├── package.json
├── vite.config.js
├── eslint.config.js
└── README.md
```

## 🚀 Getting Started

Follow these steps to run the project locally.

### Prerequisites

Make sure you have installed:

- [Node.js](https://nodejs.org/)
- npm (included with Node.js)
- Git (optional, for version control)

### Installation

**1. Clone the repository**

```bash
git clone <https://github.com/sumitmetri/AgencyAi-React-vite-Project.git>
```

**2. Navigate to the project directory**

```bash
cd Agency-AI
```

**3. Install dependencies**

```bash
npm install
```

**4. Start the development server**

```bash
npm run dev
```

Open the local URL displayed in your terminal, usually `http://localhost:5173`.

## 📜 Available Scripts

| Command | Description |
|---|---|
| `npm run dev` | Starts the development server |
| `npm run build` | Builds the application for production |
| `npm run preview` | Previews the production build locally |
| `npm run lint` | Runs ESLint to check code quality |

## 🧩 Application Architecture

The application follows a component-based structure, with individual React components responsible for different sections of the page.

- `main.jsx` initializes the React application.
- `App.jsx` combines the main sections and manages theme state.
- The `components/` directory contains reusable UI components.
- The `assets/` directory centralizes images, logos, and icons.
- Tailwind CSS handles styling and responsive layouts.
- Motion provides animations and transitions.

This structure helps keep the code organized, reusable, and easier to maintain.

## 🎨 Customization

You can customize the website by:

- Updating text and section content in the relevant component files.
- Replacing images, logos, and icons in `src/assets/`.
- Modifying global styles and theme colors in `src/index.css`.
- Adjusting animations and transitions in the components.
- Updating navigation links and section IDs in `Navbar.jsx`.

## 📦 Production Build

To create an optimized production build, run:

```bash
npm run build
```

The generated files will be available in the `dist/` directory.

To preview the production build locally, run:

```bash
npm run preview
```

## 🚀 Deployment

The live website is hosted on Netlify.

To deploy your own version, build the project and connect your Git repository to Netlify, using the following settings:

- **Build command:** `npm run build`
- **Publish directory:** `dist`

Live website: [Agency.ai](https://agencyai-react-vite.netlify.app)

## 📌 Project Purpose

This project demonstrates frontend development skills using React, reusable components, responsive styling, theme switching, and animations. It can serve as a foundation for a digital agency landing page or a portfolio website.

---

**Built with React, Vite, Tailwind CSS, and Motion.**