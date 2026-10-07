# React Hello World Task

This is a basic React application displaying "Hello, World!" as part of the Mern Stack coursework.

## Project Setup & Run
1. Install dependencies: `npm install`
2. Run the development server: `npm run dev` (for Vite) or `npm start` (for Create React App)

## Deploy to GitHub Pages

The GitHub Actions workflow in `.github/workflows/deploy.yml` builds and deploys the site whenever changes are pushed to the `main` or `master` branch. It can also be started manually from the Actions tab.

In the repository settings, set **Pages → Build and deployment → Source** to **GitHub Actions**. After pushing this project to GitHub, the deployed site URL will be shown in the workflow run.