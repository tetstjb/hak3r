# HAK3R Portfolio

This project is a free and open source portfolio template built for cybersecurity professionals using **Flowbite React** and **Vite**.

## Features

- **Modern UI:** Built with React and Flowbite components for a sleek, responsive design.
- **Light/Dark Mode:** Seamless switching between light and dark themes.
- **Optimized Performance:** Leveraging Vite for fast builds and Hot Module Replacement (HMR).
- **Customizable:** Easily modify components to suit your personal branding.
- **ESLint Configured:** Includes recommended rules with tips for production-grade, type-aware linting.

## Live Demo

[View the live demo](#) *(update this link when available)*

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v14 or later)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)

### Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/Dan-Duran/hak3r.git
cd hak3r
npm install
```

### Running the Project

Start the development server:

```bash
npm run dev
```

Then open your browser at [http://localhost:3000](http://localhost:3000) to view the portfolio.

### Building for Production

Create an optimized production build:

```bash
npm run build
```

You can preview the production build with:

```bash
npm run preview
```

## Project Structure

```
hak3r/
├── public/              # Static assets (images, CSS, etc.)
├── src/                 # React components and application code
│   ├── components/      # Reusable components (e.g., Nav, Footer)
│   └── App.tsx          # Main application component
├── package.json
├── tsconfig.json
└── README.md
```

## ESLint Configuration

For production applications, it is recommended to enable type-aware lint rules. In your ESLint configuration, set up your parser options as follows:

```js
export default {
  // other rules...
  parserOptions: {
    ecmaVersion: "latest",
    sourceType: "module",
    project: ["./tsconfig.json", "./tsconfig.node.json"],
    tsconfigRootDir: __dirname,
  },
  extends: [
    "plugin:@typescript-eslint/recommended-type-checked",
    // Optionally add:
    "plugin:@typescript-eslint/stylistic-type-checked"
  ],
};
```

## Technologies Used

- [React](https://reactjs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [Vite](https://vitejs.dev/)
- [Flowbite React](https://flowbite-react.com/)

## About

HAK3R Portfolio is designed for professionals who want to showcase their expertise with a modern, professional portfolio. Customize the template to highlight your projects, experience, and unique skills in the cybersecurity field.

## License

This project is licensed under the [MIT License](LICENSE).

---

Feel free to contribute, raise issues, or suggest enhancements.