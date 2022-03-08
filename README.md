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
Make sure to enable your less watcher, less watcher output path `$FileNameWithoutExtension$.css`
