# ReactArt - Styling React Components (Course Project)

This project was created during the **React - The Complete Guide (incl. Next.js, Redux)** training course.

It is a small React app focused on practicing different ways of styling React components while building a simple auth-style UI.

## What This App Does

- Renders a ReactArt header section with logo and tagline
- Shows an auth form with email and password inputs
- Validates input on submit:
- Email must contain `@`
- Password must be at least 6 characters
- Highlights invalid fields with conditional styling

## Styling Techniques Practiced

This training project demonstrates multiple styling approaches used in React apps:

- Utility-first styling with **Tailwind CSS v4** (current implementation)
- Component-level styling with **styled-components** (imported and available)
- Scoped CSS with **CSS Modules** (`Header.module.css`)
- Legacy plain CSS reference in `src/index-old.css`

## Tech Stack

- React 19
- Vite 5
- Tailwind CSS 4 (`@tailwindcss/vite`)
- styled-components 6
- ESLint

## Getting Started

### 1. Install dependencies

```bash
npm install
```

### 2. Start development server

```bash
npm run dev
```

Then open the local URL shown in the terminal (usually `http://localhost:5173`).

## Available Scripts

- `npm run dev` - Start Vite development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build locally
- `npm run lint` - Run ESLint checks

## Project Structure

```text
src/
	App.jsx
	main.jsx
	index.css
	index-old.css
	components/
		AuthInputs.jsx
		Button.jsx
		Header.jsx
		Header.module.css
		Input.jsx
```

## Learning Notes

- The current app uses Tailwind utility classes for most component styling.
- `Input.jsx` uses conditional class composition for invalid state styling.
- `Header.module.css` is included as part of the course practice for CSS Modules.
- `index-old.css` keeps an earlier plain-CSS version for comparison.

## Purpose

This repository is a **learning/training project** and serves as a practical playground for component styling patterns in React.