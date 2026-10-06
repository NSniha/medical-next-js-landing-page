<div align="center">

# Medical Landing Page

A fast, responsive and accessible landing page for clinics and healthcare providers, built with Next.js 16, React 19 and Tailwind CSS 4.

![Next.js](https://img.shields.io/badge/Next.js-16-black?logo=nextdotjs)
![React](https://img.shields.io/badge/React-19-61DAFB?logo=react&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-4-06B6D4?logo=tailwindcss&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?logo=javascript&logoColor=black)
![Vercel](https://img.shields.io/badge/Deployed_on-Vercel-black?logo=vercel)

[Live Demo](https://medical-next-js-landing-page.vercel.app) ·
[Report a Bug](https://github.com/NSniha/medical-next-js-landing-page/issues) ·
[Request a Feature](https://github.com/NSniha/medical-next-js-landing-page/issues)

</div>

---

## Table of Contents

- [Overview](#overview)
- [Preview](#preview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Available Scripts](#available-scripts)
- [Project Structure](#project-structure)
- [Customization](#customization)
- [Deployment](#deployment)
- [Browser Support](#browser-support)
- [Troubleshooting](#troubleshooting)
- [Contributing](#contributing)
- [Author](#author)

## Overview

**Medical Landing Page** is a front-end website template designed for clinics, hospitals, diagnostic centers and individual healthcare practitioners. It presents services and key information in a clean, trustworthy layout, helping visitors understand what a practice offers and how to get in touch.

The project is a static front end with no backend or database required, which keeps it simple to run, customize and host.

**Who is it for?**

- Clinics and healthcare providers who need a quick, professional web presence
- Developers who want a modern Next.js and Tailwind starter for a medical website
- Students learning how to structure and animate a real-world landing page

## Preview

![Medical Landing Page preview](public/images/preview.png)

> Live version: [medical-next-js-landing-page.vercel.app](https://medical-next-js-landing-page.vercel.app)

## Features

- **Responsive design:** adapts to mobile, tablet and desktop screens
- **Smooth animations:** subtle motion effects powered by Motion
- **Modern iconography:** consistent, lightweight icons from Lucide React
- **Utility-first styling:** maintainable styles with Tailwind CSS v4
- **Optimized assets:** image handling and performance benefits of Next.js
- **Clean code quality:** linting configured with ESLint and `eslint-config-next`
- **Easy to customize:** update content, images and colors without touching any backend
- **One-click deployment:** ready to deploy on Vercel

## Tech Stack

| Category     | Technology                                      |
|--------------|-------------------------------------------------|
| Framework    | [Next.js 16](https://nextjs.org)                |
| UI Library   | [React 19](https://react.dev)                   |
| Styling      | [Tailwind CSS 4](https://tailwindcss.com) with PostCSS |
| Animation    | [Motion](https://motion.dev)                    |
| Icons        | [Lucide React](https://lucide.dev)              |
| Language     | JavaScript (ES6+)                               |
| Linting      | [ESLint 9](https://eslint.org)                  |
| Hosting      | [Vercel](https://vercel.com)                    |

## Getting Started

### Prerequisites

- **Node.js** 20.9 or later
- **npm** (comes with Node.js), or yarn / pnpm
- **Git**

Check your versions:

```bash
node -v
npm -v
```

### Installation

1. Clone the repository

   ```bash
   git clone https://github.com/NSniha/medical-next-js-landing-page.git
   ```

2. Move into the project directory

   ```bash
   cd medical-next-js-landing-page
   ```

3. Install dependencies

   ```bash
   npm install
   ```

4. Start the development server

   ```bash
   npm run dev
   ```

5. Open [http://localhost:3000](http://localhost:3000) in your browser. The page reloads automatically as you edit files.

## Available Scripts

| Command         | Description                                   |
|-----------------|-----------------------------------------------|
| `npm run dev`   | Starts the development server with hot reload |
| `npm run build` | Creates an optimized production build         |
| `npm start`     | Serves the production build                   |
| `npm run lint`  | Runs ESLint to check code quality             |

To preview the production version locally:

```bash
npm run build
npm start
```

## Project Structure

```
medical-next-js-landing-page/
├── public/
│   └── images/            # Static images used across the page
├── src/                   # Application source code (pages, components, styles)
├── .gitignore
├── eslint.config.mjs      # ESLint configuration
├── jsconfig.json          # JavaScript path configuration
├── next.config.mjs        # Next.js configuration
├── postcss.config.mjs     # PostCSS configuration for Tailwind CSS
├── package.json           # Dependencies and scripts
└── README.md
```

## Customization

| What to change      | Where                                                        |
|---------------------|--------------------------------------------------------------|
| Images and logos    | Replace files in `public/images`                             |
| Page content        | Edit the page and component files inside `src`               |
| Colors and spacing  | Update Tailwind utility classes or theme values in the styles |
| Icons               | Swap icons from the [Lucide icon library](https://lucide.dev/icons) |
| Animations          | Adjust Motion settings in the relevant components            |
| SEO title and meta  | Update the metadata in the root layout file                  |

## Deployment

### Deploy on Vercel (recommended)

1. Push the project to your GitHub account
2. Sign in to [Vercel](https://vercel.com) and click **Add New Project**
3. Import the repository. Vercel detects Next.js automatically
4. Click **Deploy**

Every push to the `main` branch is then deployed automatically.

### Other platforms

Any platform that supports Node.js can host the app. Run `npm run build` followed by `npm start`.

## Browser Support

Works on the latest versions of Chrome, Edge, Firefox and Safari, on desktop and mobile.

## Troubleshooting

**`npm install` fails or shows engine warnings**
Make sure you are using Node.js 20.9 or later.

**Port 3000 is already in use**
Run the app on another port: `npm run dev -- -p 3001`

**Styles are not applying**
Stop the server, delete the `.next` folder and run `npm run dev` again.

## Contributing

Contributions, issues and feature requests are welcome.

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/your-feature`
3. Commit your changes: `git commit -m "Add your feature"`
4. Push to the branch: `git push origin feature/your-feature`
5. Open a Pull Request

Please run `npm run lint` before submitting.

## Author

**NSniha**
GitHub: [@NSniha](https://github.com/NSniha)

---

<div align="center">

If you find this project useful, consider giving it a star.

</div>
