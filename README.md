## Basic Webpack Config

This files provides the basic structure of [Webpack 4](https://webpack.js.org/) to start up and running.

With this _extremely simple_ setup you will be able to write your HTML, JS(ES6, ES7, ES+), CSS(SCSS, SASS) just the way you like it and when you run `npm run build` it will compile and minify everything into the "bundle" folder that will be created at the root of the project.

## Additionaly

This setup includes three helpers files located at `./src/SASS/helpers` that are already imported in the existing "main.scss" file.

These helper files already include all the media queries you may need, it includes all the vendor prefixers for all existing [Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) properties, and the minified CSS output will only include the mixins and variables you've used during development so you don't have to worry about having an overly large file on production. This file will be minified and will include only what you've used.

### Notice

The HTML will be compressed; all your CSS, SASS, and/or SCSS files will be transpiled to a minified CSS file. Your JavaScript will be transpiled to ES5 to ensure wider support accross broswers.

### Remember!

You just have to FORK this project and then clone it to your computer.

In case you just cloned the repo first remember to change your git's remote before pushing changes, if you don't, the "origin" remote will be this same repository. You need to change that to your own project's repository before commiting your changes. To change that you can run the command below in your terminal:

```
git remote set-url origin https://github.com/{{ USERNAME }}/{{ YOU REPO }}.git
```
