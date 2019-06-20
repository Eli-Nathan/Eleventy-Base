# Eleventy | Gulp

A base project using Eleventy as a static site generator and Gulp to compile assets

## Features 

- This project uses Eleventy as a static site generator
- Templating is using Liquid 
- SCSS/JS compiling with Gulp 
- Babel to transpile and bundle JS
- A good handful of SEO meta tags set up

## Getting started

1. Clone the repo 

```
git clone https://github.com/eli-nathan/eleventy-base.com
```

2. Use correct Node.js version

```bash
nvm install
```

2. Install dependencies

```bash
npm install
```

3. Start development server

```bash
npm start
```

4. Create a local build (optional)
>The build happens on the pipeline during deployment but you can run it locally to inspect what the production build will look like.

```
npm run build
```

## Development
Edit `/src/index.html` as the homepage.

Add pages in `/src/assets/stylesheets/` and import them into `/src/assets/stylesheets/styles.scss` and they will be compiled into the build directory.

Write JavaScript in `/src/assets/scripts/`. This project is setup to use [ReactJS](https://reactjs.org/) using Babel so feel free to `import React, { Component } from 'react';`!

Create [Collections](https://www.11ty.io/docs/collections/) for posts and similar templated content.

After adding images, you will need to restart the server 🚀