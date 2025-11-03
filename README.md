# Prompt Library

A modern, lightweight prompt management library built with Next.js for saving, organizing, and reusing AI prompts.

## Features

- Save and organize AI prompts
- Search and filter through your prompt collection
- Copy prompts to clipboard for quick reuse
- Tag and categorize prompts for easy organization
- Responsive design with dark mode support
- Built with modern React and TypeScript

## Tech Stack

- **Framework**: [Next.js 16](https://nextjs.org) (App Router)
- **Language**: TypeScript
- **Styling**: [Tailwind CSS v4](https://tailwindcss.com)
- **Linting & Formatting**: [Biome](https://biomejs.dev)
- **React**: React 19.2 with React Compiler enabled

## Getting Started

### Prerequisites

- Node.js 20.x or later
- npm, yarn, pnpm, or bun

### Installation

```bash
# Clone the repository
git clone git@github.com:Goku-kun/prompt-library.git

# Navigate to the project directory
cd prompt-library

# Install dependencies
npm install
```

### Development

Run the development server:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to see the application.

The page auto-updates as you edit files in the `app` directory.

### Available Scripts

- `npm run dev` - Start the development server
- `npm run build` - Build the application for production
- `npm start` - Start the production server
- `npm run lint` - Run Biome linter
- `npm run format` - Format code with Biome

## Project Structure

```
prompt-library/
├── app/                 # Next.js App Router directory
│   ├── layout.tsx      # Root layout component
│   ├── page.tsx        # Home page
│   └── globals.css     # Global styles
├── public/             # Static assets
├── biome.json          # Biome configuration
├── next.config.ts      # Next.js configuration
├── postcss.config.mjs  # PostCSS configuration
├── tsconfig.json       # TypeScript configuration
└── package.json        # Project dependencies
```

## Configuration

### React Compiler

This project uses the React Compiler for optimized rendering. The compiler is configured in `next.config.ts`:

```typescript
reactCompiler: true
```

### Tailwind CSS v4

The project uses Tailwind CSS v4 with the new PostCSS plugin architecture. Configuration is handled through `postcss.config.mjs`.

## Code Quality

This project uses [Biome](https://biomejs.dev) for linting and formatting, providing:

- Fast performance
- Unified tooling (no need for ESLint + Prettier)
- Consistent code style enforcement

Run code quality checks:

```bash
# Check for issues
npm run lint

# Auto-fix and format
npm run format
```

## Deployment

### Vercel (Recommended)

The easiest way to deploy is using the [Vercel Platform](https://vercel.com/new):

1. Push your code to GitHub
2. Import the repository in Vercel
3. Vercel will automatically detect Next.js and deploy

### Other Platforms

Build the production bundle:

```bash
npm run build
```

Start the production server:

```bash
npm start
```

For more deployment options, see the [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying).

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

[MIT](LICENSE)

## Learn More

- [Next.js Documentation](https://nextjs.org/docs)
- [Next.js on GitHub](https://github.com/vercel/next.js)
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)
- [Biome Documentation](https://biomejs.dev)
