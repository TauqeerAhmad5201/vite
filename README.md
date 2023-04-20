# vite

Vite (French word for "quick", pronounced /vit/ , like "veet") is a build tool that aims to provide a faster and leaner development experience for modern web projects.

## Working 

Vite uses esbuild to pre-bundle the dependencies and then immediately launches the server. It then analyzes the code and processes via route-based code splitting. Vite then uses native ESM support to deliver the code. This enables the browser to do the bundling and development. To implement other performance optimizations, Vite uses Rollup, which bundles the application. 

## Why Vite.js?

There are several advantages of using Vite:
Hot Module Replacement

Hot Module Replacement (HMR) adds, updates, or removes modules while an application runs without reloading the entire page. This helps speed up the development process as it only updates the changes we just made and retains the application state lost during reloading. It also makes the application incredibly fast regardless of the app size.
Configuration

We can have complete control over the project by extending the default configuration with vite.config.js or vite.config.ts file files in the working directory. A basic config file looks like this:

```// vite.config.js
export default {
  // config options
}
```
## Conclusion

Vite is an incredible build tool that is relatively new to the market. Its unique features, speedier developer experience, and support for different languages have already been pretty popular among developers. It's great when we want to avoid using a framework but do need minified scripts and styles.
