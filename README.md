# Simple Poem Site - IDMX 11ty Sass Starter

The site shows the poem _Who Has Seen the Wind?_ by Christina Rossetti and an image used to represent the poem by Markus Spiske on Unsplash.

The set of development scripts in this starter is configured to watch and compile a simple Sass structure using 11ty.

The code is located in the `src` folder and the page is created in the `public` folder.

The `settings.json` in the `.vscode` folder sets the `LiveServer` configuration to serve from the `public` folder and can be used to serve the built page.

The build process includes minifiying and autoprefixing of styles via the `postbuild` script, which runs automatically after a `build`.

## Installation

**`npm install`**

> Run this command once to install the needed node modules.

## Development Scripts

**`npm start`**

> This script runs 11ty with hot reload and served at the url localhost:8080. It will reload whenever there are HTML or Sass changes.

**`npm run build`**

> This script does a production build and includes minified, autoprefixed CSS.

Use this as the "Publish command" if needed by hosting services such as Netlify.

## Resources

<small>The starter was inspired by [11ty Sass Skeleton](https://github.com/5t3ph/11ty-sass-skeleton) by [@5t3ph](https://twitter.com/5t3ph)</small>

- Link to Christina Rossetti's [poem](https://poets.org/poem/who-has-seen-wind)
- Link to Markus Spiske's [image](https://unsplash.com/photos/QHQYCrSriPA)

## Code Attribution for CSS

The template for the code below is from Andy Bell's [presentation](https://www.youtube.com/watch?v=5uhIiI9Ld5M) (Section starts from 25:24 - 28:03)

```
:root {
--flow-space: 3rem;
}

.flow > * + * {
margin-top: var(--flow-space, 1em);
}
```
