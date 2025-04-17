# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Information
- Astro.js application with React integration
- TailwindCSS for styling
- Custom shader backgrounds implemented in JavaScript

## Commands
- `npm run dev` - Start the development server
- `npm run build` - Build the project for production
- `npm run preview` - Preview the production build locally

## Code Style Guidelines
- Use TypeScript when possible (types are configured)
- Default to functional components for React
- Follow Astro component structure with frontmatter, markup, and styles
- Props destructuring with default values at the top of components
- Responsive design using Tailwind classes (sm:, md:, etc.)
- Error handling with try/catch in complex functions
- Prefer async/await for asynchronous code
- Use camelCase for variables/functions, PascalCase for components
- Consistent 2-space indentation

## Formatting
- Prettier is configured with Astro and Tailwind plugins
- Run `npx prettier --write .` to format code