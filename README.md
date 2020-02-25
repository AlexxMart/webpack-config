## Basic Webpack Config

This files provides the basic structure of [Webpack 4](https://webpack.js.org/) to start up and running.

With this _extremely simple_ setup you will be able to write your HTML, JS(ES6, ES7, ES+), CSS(SCSS, SASS) just the way you like and when you run `npm run build` it will compile and compress everything into the "bundle" folder that will be created when the command is ran.

## Additionaly

This setup includes three helpers files located at `./src/SASS/helpers` that are already imported in the existing "main.scss" file. These helper files already include all the media queries you may need and include all the vendor prefixers for all existing [Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) properties.

### Notice

The HTML will be compressed, all your CSS, SASS, SCSS file be transpiled to a minified CSS file, and you JS will be transpiled to ES5 to ensure wider support accross broswers.

### Remember!

Remember to change your git's remote before pushing changes to your project. After you clone this repo, the "origin" remote will be this same repository, so you need to change that to your own project's repository before commiting your changes. To change that you can run the command below in your terminal:

```
git remote set-url origin https://github.com/USERNAME/REPOSITORY.git
```
