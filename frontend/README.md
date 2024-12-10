# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Run the following comands to set the environment:

### `npm create vite@latest .`

### `npm install`

### `npm install -D tailwindcss postcss autoprefixer`

### `npx tailwindcss init -p`

### `npm i -D daisyui@latest`

### `npm install react-icons --save`

### `npm i react-router-dom`

### `npm i react-hot-toast`

## Rewrite your tailwind.config.js file:

/** @type {import('tailwindcss').Config} \*/
export default {
content: ["./index.html","./src/**/\*.{js,ts,jsx,tsx}",],
theme: {extend: {},},
plugins: [require('daisyui'),],
}

## Rewrite your ./src/index.css file:

@tailwind base;
@tailwind components;
@tailwind utilities;

## And finally run the app in development mode:

### `npm run dev`
