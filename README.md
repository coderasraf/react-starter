# React Starter

A minimal Create React App boilerplate preconfigured with ESLint (Airbnb rules), Prettier and VS Code settings, used as a clean starting point for new React projects.

![React](https://img.shields.io/badge/React-17-61DAFB?logo=react&logoColor=white) ![ESLint](https://img.shields.io/badge/ESLint-Airbnb-4B32C3?logo=eslint&logoColor=white) ![Prettier](https://img.shields.io/badge/Prettier-2.5-F7B93E?logo=prettier&logoColor=black)

## Overview

Set up in early 2022 as a reusable starter while learning React. The app itself only renders "Hello world"; the value is in the tooling configuration so linting and formatting work out of the box.

## Features

- Create React App 5 (react-scripts 5.0.0) with React 17
- `.eslintrc` extending `airbnb`, `airbnb/hooks`, `eslint:recommended`, `prettier` and `plugin:jsx-a11y/recommended`
- Prettier enforced through `eslint-plugin-prettier` (single quotes, 4-space tabs, 100-char lines, ES5 trailing commas, semicolons)
- React Hooks rules enforced as errors
- `.vscode/settings.json` with ESLint fix-on-save, organize imports and Emmet enabled for JSX
- Testing Library (`@testing-library/react`, `jest-dom`, `user-event`) and `web-vitals` included

## Tech Stack

- React 17, Create React App 5
- ESLint 8 configs: Airbnb, Prettier, jsx-a11y, react, react-hooks, import
- Prettier 2.5
- Jest + React Testing Library

## Getting Started

Prerequisites: Node.js 14+ and npm.

```bash
git clone https://github.com/coderasraf/react-starter.git my-app
cd my-app
npm install
npm start        # http://localhost:3000
```

Other scripts:

| Command | Description |
| --- | --- |
| `npm test` | Run tests in watch mode |
| `npm run build` | Production build to `build/` |
| `npm run eject` | Eject from Create React App (one-way) |

For the editor setup to work, install the ESLint and Prettier extensions in VS Code.

## Project Structure

```text
.vscode/settings.json   # Format/lint on save, Emmet for JSX
.eslintrc               # Airbnb + Prettier lint rules
public/                 # index.html, manifest, robots.txt
src/
├── App.js              # "Hello world" component
├── index.js            # Entry point
├── reportWebVitals.js
└── setupTests.js
```

## Author

Built by **Ashraf Siddik**, Shopify developer & CRO specialist.
- Website: [ashraf-siddik.com](https://ashraf-siddik.com)
- GitHub: [@coderasraf](https://github.com/coderasraf)
