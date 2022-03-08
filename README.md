# Readme

## Installation
> npm install

## Build Tailwind css file
Run npm script `build` from package.json  
or
> npm tailwind build -i ./css/src/tailwind-src.css -o ./css/style.css

---

### @apply tailwind classes in your custom file
Use `/css/main.less` to apply properties to classes and re-build to include in single output file.
Output file is `/css/style.css`, configured in your `package.json`.

### Less to Css 
- Less, it's CSS with just a little more [lesscss.org](https://lesscss.org/)
- Get less via npm [package](https://www.npmjs.com/package/less)
- JetBrains (PhpStorm, WebStorm) watcher [configuration](https://www.jetbrains.com/help/phpstorm/transpiling-sass-less-and-scss-to-css.html#ws_sass_less_scss_syntax_highlighting)

Make sure to enable your less watcher, less watcher output path `$FileNameWithoutExtension$.css`.
