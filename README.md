# Ten

A modern Vue 3 application built with TypeScript, Vite, Tailwind CSS, DaisyUI, and VueUse.

## Tech Stack

- [Vue 3](https://vuejs.org/) - Progressive JavaScript framework
- [TypeScript](https://www.typescriptlang.org/) - JavaScript with syntax for types
- [Vite](https://vitejs.dev/) - Next-generation frontend tooling
- [Tailwind CSS](https://tailwindcss.com/) - Utility-first CSS framework
- [DaisyUI](https://daisyui.com/) - Tailwind CSS component library
- [VueUse](https://vueuse.org/) - Collection of Vue Composition API utilities

## Getting Started

### Prerequisites

- Node.js
- npm or Bun (project uses Bun)

### Installation

```bash
# Clone the repository
git clone <repository-url>
cd ten

# Install dependencies
bun install
```

### Development

```bash
# Start development server
bun run dev
```

### Build

```bash
# Build for production
bun run build
```

## Project Structure

```plaintext
ten/
├── public/           # Static assets
├── src/              # Source code
│   ├── assets/       # Project assets (images, fonts, etc.)
│   ├── components/   # Vue components
│   ├── App.vue       # Root component
│   ├── main.ts       # Entry point
│   └── style.css     # Global styles with Tailwind
├── index.html        # HTML entry point
└── vite.config.ts    # Vite configuration
```

## Features

- Modern Vue 3 Composition API with `<script setup>`
- Type-safe development with TypeScript
- Fast development and build with Vite
- Beautiful UI with Tailwind CSS and DaisyUI components
- Collection of useful composition utilities from VueUse

## Learn More

- [Vue 3 Documentation](https://vuejs.org/)
- [TypeScript Documentation](https://www.typescriptlang.org/)
- [Vite Documentation](https://vitejs.dev/)
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)
- [DaisyUI Documentation](https://daisyui.com/docs)
- [VueUse Documentation](https://vueuse.org/)
