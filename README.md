# Project viewer Showcase

### This repository is a showcase repository for the website built with Vite, React, TypeScript, and GraphQL. The website aims to provide a clean and intuitive interface for showcasing projects, with features such as project filtering and README viewing.

## Project Structure
```
src
├── api
│   ├── fetchProjects.ts
│   └── manageIndexedDB.ts
├── App.css
├── App.tsx
├── assets
├── components
│   ├── FilterTabs.tsx
│   └── ProjectCard.tsx
├── constants.ts
├── index.css
├── interface.d.ts
├── main.tsx
├── sections
│   ├── HeaderSection.tsx
│   └── ProjectSection.tsx
└── vite-env.d.ts
```

- api: Contains modules for fetching project data and managing IndexedDB.
- components: Houses React components used throughout the application, such as FilterTabs and ProjectCard.
- sections: Contains specific sections of the website, such as HeaderSection and ProjectSection.
- assets: Stores static assets used in the project.
- App.css and index.css: CSS files for styling the application.
- App.tsx and main.tsx: Entry points for the React application.
- constants.ts: Defines constants used throughout the application.
- interface.d.ts and vite-env.d.ts: TypeScript declaration files for type definitions and Vite environment setup.
