# cloudGenesis

Hugo website to explore cloud idea, built with Tailwind CSS.

## Features

- Hugo static site generator
- Tailwind CSS v4 for styling
- PostCSS processing with Autoprefixer
- Dark mode support
- Responsive design templates

## Prerequisites

- [Hugo](https://gohugo.io/installation/) (extended version recommended)
- [Node.js](https://nodejs.org/) and npm

## Getting Started

1. Install dependencies:
```bash
npm install
```

2. Run the development server:
```bash
npm run dev
```

The site will be available at `http://localhost:1313`

3. Build for production:
```bash
npm run build
```

## Project Structure

- `assets/css/` - CSS source files with Tailwind imports
- `content/` - Markdown content files
- `layouts/` - Hugo templates with Tailwind utility classes
- `static/` - Static assets
- `public/` - Generated site (created on build)

## Adding Content

Create new content with:
```bash
hugo new content/posts/my-post.md
```

## Customization

- Edit `hugo.toml` to configure site settings
- Modify templates in `layouts/` to change structure
- Add Tailwind classes to templates for styling
- Customize `assets/css/main.css` for additional styles
