# Pure Shilajit Store Shopify Theme

A Shopify theme created for [pureshilajitstore.com](https://pureshilajitstore.com/). This theme includes custom Shopify sections, snippets, templates, and a modern frontend build pipeline using Webpack, React, and Tailwind CSS.

## Features

- Shopify theme structure with `layout`, `templates`, `sections`, `snippets`, `assets`, `config`, and `locales`
- Custom Shopify storefront components and layout styles
- Modern frontend build using:
  - Webpack
  - React
  - Tailwind CSS
  - PostCSS
  - ESBuild loader
- Asset output bundle:
  - `assets/react-bundle.js`
  - `assets/tailwind-compiled.css`

## Project Structure

- `assets/` - theme static assets, styles, scripts, and compiled bundles
- `config/` - theme settings and schema configuration
- `layout/` - theme layout files such as `theme.liquid`
- `locales/` - translations and locale JSON files
- `sections/` - customizable Liquid sections used by Shopify pages
- `snippets/` - reusable Liquid snippets
- `src/` - frontend source code for React and Tailwind
- `templates/` - Shopify templates for pages, products, collections, etc.

## Requirements

- Node.js 18+ recommended
- npm or Yarn
- Shopify CLI / Shopify admin for theme deployment

## Setup

1. Install dependencies:

```bash
npm install
```

2. Run local build for development:

```bash
npm run dev
```

3. Build for production:

```bash
npm run build
```

## Build Details

- Webpack entry point: `src/index.jsx`
- Output bundle: `assets/react-bundle.js`
- CSS output via `MiniCssExtractPlugin`: `assets/tailwind-compiled.css`
- Uses `esbuild-loader` for fast JSX/JavaScript compilation
- Uses `postcss-loader` and `tailwindcss` for styles

## Notes

- This theme is designed specifically for the Pure Shilajit Store storefront.
- If deploying to Shopify, ensure compiled assets are included in the theme upload.
- Adjust the theme schema and section settings as needed for storefront customization.

## Author

- Mehedi Hasan
