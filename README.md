# 👋 React Page

A clean, minimal "Hello World" starter built with **React 19** and **Vite 8**. This is a first step into React — a small, well-organized playground for learning the fundamentals of components, state, and the modern Vite dev workflow.

## ✨ Features

- ⚛️ **React 19** with functional components and hooks (`useState`)
- ⚡ **Vite 8** for instant dev server startup and lightning-fast HMR
- 🎨 Custom styling with a hero image and interactive counter button
- 🧹 **ESLint** configured with React Hooks and React Refresh rules
- 🗂️ Simple, readable project structure — easy to extend

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) 18+
- npm (bundled with Node.js)

### Installation

```bash
# Clone the repository
git clone <your-repo-url>
cd webpage-hello-world-react

# Install dependencies
npm install
```

### Development

```bash
npm run dev
```

Then open the printed local URL (typically `http://localhost:5173`) in your browser.

## 📜 Available Scripts

| Command           | Description                              |
| ----------------- | ----------------------------------------- |
| `npm run dev`     | Start the Vite dev server with HMR        |
| `npm run build`   | Build an optimized production bundle      |
| `npm run preview` | Preview the production build locally      |
| `npm run lint`    | Run ESLint across the project             |

## 🗂️ Project Structure

```
├── public/            # Static assets (favicon, icon sprite)
├── src/
│   ├── assets/        # Images used by the app
│   ├── App.jsx        # Main app component
│   ├── App.css        # App-level styles
│   ├── index.css      # Global styles
│   └── main.jsx       # React entry point
├── index.html         # HTML entry point
└── vite.config.js     # Vite configuration
```

## 🛠️ Tech Stack

- [React](https://react.dev/)
- [Vite](https://vite.dev/)
- [ESLint](https://eslint.org/)

## 📄 License

This project is open source and available for personal or educational use.
