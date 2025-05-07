# Octopus Maps Project
This project runs on [11ty](https://www.11ty.dev/), [tailwindcss](https://tailwindcss.com/), and [daisyui](https://daisyui.com/). 

**Important note**: please do not store unprocessed images with `.jpg`, `.png`, etc. extensions in the repository (or any binary file larger than 1MB in size). Over time, this will take up a lot of space on our computers. Instead, make sure all images have been converted into `.webp` format using an [online converter](https://cloudconvert.com/webp-converter) before storing them in the repository. 

## To use
1. Download or clone the repository (or fetch from the origin)
2. In the terminal: `npm install` to download the dependencies
3. Then: `npm run dev` to build and start the dev server 
4. Visit [http://localhost:8080](http://localhost:8080) to view the site
5. To stop the server (in order to change configurations or recompile tailwind, for example) just press `control + C` (on a mac), then `npm run dev` again to rebuild.

## Notes
This is a fairly standard implementation with only a few customizations. Below are the most notable files and their basic functions.

### in `/package.json`
+ dependencies are declared
+ npm scripts are defined
+ project details are specified
+ used to generate `package-lock.json` during build step

### in `src/styles/index.css`
+ installs tailwind and plugins
+ Implements fonts from google fonts
+ sets daisyUI themes for light and dark mode (currently set to autumn)

### in `/eleventy.config.mjs`
+ Files are read from `/src` and built to `/dist`
+ Templating is done with nunjucks `.njk` by default
+ Content pages are in markdown `.md` (with native HTML processing)
+ The `src/assets` directory is passed through to `dist`

### in `/tailwind.config.js`
+ Theme is extended to use fonts with `.font-playfair` and `.font-poppins` classes
+ nothing else happens here yet

### in `/src/_includes`
+ Base template is `default.njk`
+ Nav and footer components 

### in `/src/assets`
+ for now this is so images are passed into the `dist` directory
+ later it can be used for any file assets

