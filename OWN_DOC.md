# Personal DOC FROM THE package

- Using `npm` to manage the package (node package manager). Main alternative: `yarn`. Few differences as of today. `pnpm` uses symlink on your machine (to prevent many installs)
- Using `rollup` to run the package. It is a **module bundler** Alternative: webpack. Goal is to launch a working version, ready to be run in the browser. `Vite` is apreconfiguration of rollup. **A bundler is A bundler is a development tool that combines multiple JavaScript code files into a single one that can be loaded in the browser and used in production.**. Very briefly: `rollup` for library/apps, `webpack` to be loaded in the browser.

Note on JS:  
- "This finally changed with the ES6 revision of JavaScript, which includes a syntax for importing and exporting functions and data so they can be shared between separate scripts.". But it does not work on all browsers so "Rollup allows you to write your code using the new module system, and will then compile it back down to existing supported formats such as CommonJS modules, AMD modules, and IIFE-style scripts."
- **Tree-shaking** is removing what will not be used
