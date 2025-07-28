# vue-project

This template should help get you started developing with Vue 3 in Vite.

## 🚀 Live Demo

This project is automatically deployed to GitHub Pages: [View Live Site](https://username.github.io/om-helper/)

## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur).

## Type Support for `.vue` Imports in TS

TypeScript cannot handle type information for `.vue` imports by default, so we replace the `tsc` CLI with `vue-tsc` for type checking. In editors, we need [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) to make the TypeScript language service aware of `.vue` types.

## Customize configuration

See [Vite Configuration Reference](https://vite.dev/config/).

## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Type-Check, Compile and Minify for Production

```sh
npm run build
```

### Deploy to GitHub Pages

The project is configured for automatic deployment to GitHub Pages via GitHub Actions. Every push to the main branch will trigger a new deployment.

#### Manual Deployment (Alternative)

If you prefer manual deployment, you can use:

```sh
npm run deploy
```

**Note:** For manual deployment, you'll need to install the gh-pages dependency first:

```sh
npm install
```

#### Deployment Configuration

- **Base Path**: Configured for GitHub Pages repository deployment (`/om-helper/`)
- **SPA Routing**: Includes 404.html fallback for client-side routing
- **GitHub Actions**: Automated deployment workflow in `.github/workflows/deploy.yml`

### Lint with [ESLint](https://eslint.org/)

```sh
npm run lint
```

## GitHub Pages Setup

To enable GitHub Pages for this repository:

1. Go to your repository settings on GitHub
2. Navigate to "Pages" in the left sidebar
3. Under "Source", select "GitHub Actions"
4. The site will be available at `https://username.github.io/repository-name/`

The deployment workflow will automatically build and deploy your site whenever you push to the main branch.
