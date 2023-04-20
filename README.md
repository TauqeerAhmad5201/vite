# vite

Vite (French word for "quick", pronounced /vit/ , like "veet") is a build tool that aims to provide a faster and leaner development experience for modern web projects.

## working 

Vite uses esbuild to pre-bundle the dependencies and then immediately launches the server. It then analyzes the code and processes via route-based code splitting. Vite then uses native ESM support to deliver the code. This enables the browser to do the bundling and development. To implement other performance optimizations, Vite uses Rollup, which bundles the application. 
