<div> 
</h1> Medical Landing Page</h1> <p><b>A modern website for clinics and healthcare providers.</b><br> Present your services clearly, build patient trust, and make it easy to get in touch.</p> <img src="https://skillicons.dev/icons?i=nextjs,react,tailwind,js,vercel&perline=5" alt="Next.js, React, Tailwind CSS, JavaScript, Vercel" />
<br><br>
<a href="https://medical-next-js-landing-page.vercel.app"><img src="https://img.shields.io/badge/Live_Demo-Visit_Site-0A66C2?style=for-the-badge&logo=vercel&logoColor=white" alt="Live Demo" /></a> <a href="https://github.com/NSniha/medical-next-js-landing-page/issues"><img src="https://img.shields.io/badge/Report-Issue-D73A49?style=for-the-badge&logo=github&logoColor=white" alt="Report an issue" /></a>
<br><br>
<img width="1280" height="800" alt="preview" src="https://github.com/user-attachments/assets/647ba420-5d86-4cf8-9034-287c4bd8a1b6" />
</div>

---

## Overview

**Medical Landing Page** is a front-end website template designed for clinics, hospitals, diagnostic centers and individual healthcare practitioners. It presents services and key information in a clean, trustworthy layout, helping visitors understand what a practice offers and how to get in touch.

The project is a static front end with no backend or database required, which keeps it simple to run, customize and host.

**Who is it for?**

- Clinics and healthcare providers who need a quick, professional web presence
- Developers who want a modern Next.js and Tailwind starter for a medical website
- Students learning how to structure and animate a real-world landing page


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
 
Built with a modern, lightweight front-end toolchain. No backend or database required.
 
<table>
  <tr>
    <td align="center" width="140">
      <a href="https://nextjs.org"><img src="https://skillicons.dev/icons?i=nextjs" width="56" alt="Next.js" /></a><br />
      <b>Next.js 16</b><br />
      <sub>Framework</sub>
    </td>
    <td align="center" width="140">
      <a href="https://react.dev"><img src="https://skillicons.dev/icons?i=react" width="56" alt="React" /></a><br />
      <b>React 19</b><br />
      <sub>UI library</sub>
    </td>
    <td align="center" width="140">
      <a href="https://tailwindcss.com"><img src="https://skillicons.dev/icons?i=tailwind" width="56" alt="Tailwind CSS" /></a><br />
      <b>Tailwind CSS 4</b><br />
      <sub>Styling</sub>
    </td>
    <td align="center" width="140">
      <a href="https://motion.dev"><img src="https://cdn.simpleicons.org/framer/0055FF" width="48" height="56" alt="Motion" /></a><br />
      <b>Motion</b><br />
      <sub>Animations</sub>
    </td>
  </tr>
  <tr>
    <td align="center" width="140">
      <a href="https://lucide.dev"><img src="https://cdn.simpleicons.org/lucide/F56565" width="48" height="56" alt="Lucide" /></a><br />
      <b>Lucide React</b><br />
      <sub>Icons</sub>
    </td>
    <td align="center" width="140">
      <a href="https://developer.mozilla.org/docs/Web/JavaScript"><img src="https://skillicons.dev/icons?i=js" width="56" alt="JavaScript" /></a><br />
      <b>JavaScript</b><br />
      <sub>Language</sub>
    </td>
    <td align="center" width="140">
      <a href="https://eslint.org"><img src="https://skillicons.dev/icons?i=eslint" width="56" alt="ESLint" /></a><br />
      <b>ESLint 9</b><br />
      <sub>Code quality</sub>
    </td>
    <td align="center" width="140">
      <a href="https://vercel.com"><img src="https://skillicons.dev/icons?i=vercel" width="56" alt="Vercel" /></a><br />
      <b>Vercel</b><br />
      <sub>Hosting</sub>
    </td>
  </tr>
</table>

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
