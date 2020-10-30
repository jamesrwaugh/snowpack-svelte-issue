# To Reproduce Issue

- Run app
- Click the button
- Note in the Console

```
sveltestrap.js:196 Uncaught (in promise) TypeError: Cannot read property 'c' of undefined
    at gt (sveltestrap.js:196)
    at Object.o (sveltestrap.js:675)
    at transition_out (internal.js:154)
    at Object.o (App.js:63)
    at transition_out (internal.js:154)
    at Object.p (App.js:197)
    at update (internal.js:116)
    at flush (internal.js:84)
```

# New Project

> ✨ Bootstrapped with Create Snowpack App (CSA).

## Available Scripts

### npm start

Runs the app in the development mode.
Open http://localhost:8080 to view it in the browser.

The page will reload if you make edits.
You will also see any lint errors in the console.

### npm test

Launches the test runner in the interactive watch mode.
See the section about running tests for more information.

### npm run build

Builds a static copy of your site to the `build/` folder.
Your app is ready to be deployed!

**For the best production performance:** Add a build bundler plugin like [@snowpack/plugin-webpack](https://github.com/snowpackjs/snowpack/tree/master/plugins/plugin-webpack) or [snowpack-plugin-rollup-bundle](https://github.com/ParamagicDev/snowpack-plugin-rollup-bundle) to your `snowpack.config.json` config file.

### Q: What about Eject?

No eject needed! Snowpack guarantees zero lock-in, and CSA strives for the same.
