
<h2 align="center">webpack-sass-bootstrap-boilerplate</h2>

<p align="center">
  <a href="https://github.com/shaminmeerankutty/webpack-sass-bootstrap-boilerplate/blob/master/LICENSE.md">
    <img alt="License" src="https://img.shields.io/github/license/mashape/apistatus.svg"></a>
  <a href="https://webpack.js.org">
    <img alt="Webpack" src="https://img.shields.io/badge/webpack-v4.25.1-0072b8.svg"></a>
  <a href="http://getbootstrap.com/">
    <img alt="Bootstrap" src="https://img.shields.io/badge/Bootstrap-v4.1.3-563d7c.svg"></a>
  <a href="https://sass-lang.com">
    <img alt="Sass" src="https://img.shields.io/badge/node--sass-v4.10.0-df5a9c.svg"></a>
  <a href="https://jquery.com/">
    <img alt="jQuery" src="https://img.shields.io/badge/jquery-v3.3.1-ffa200.svg"></a>
  <a href="">
    <img alt="Webpack Dev Server" src="https://img.shields.io/badge/webpack--dev--server-live--reloading-orange.svg"></a>
</p>

<p align="center">
  <em>
  Sass
  · Babel
  · Bootstrap
  · Webpack
  · Webpack Dev Server
  · jQuery 3.3.1
  · Popper.js 
  </em>
</p>

This Webpack Sass Bootstrap boilerplate starter contains the features and scripts you need
to get started quickly with Webpack bundling and building, Live Loading, and creating a dev server.

It contains the following features:

- Webpack 4 bundling
- Babel ES6 Compiler
- Sass Compiler
- Bootstrap v4
- jQuery 3.3.1
- Popper.js 
- Webpack Dev Server

## Check Out Our Documentation
If you want to check out our official documentation, just click [here](https://shaminmeerankutty.github.io/webpack-sass-bootstrap-boilerplate/). 

It contains guidance on setting up this starter, as well as feature outlines.

## Features

### Webpack Loaders
This starter contains the following webpack loaders:

* Sass Loader for compiling sass (SCSS)
* File Loader for loading asset files
* HTML Loader for loading HTML files
* Babel Loader for compiling ES6 code

### Webpack Plugins 
The following webpack plugins are also included:

* Extract Text Plugin for extracting CSS files
* Clean Webpack Plugin for cleaning unwanted files in dist directory
* HTML Webpack Plugin for generating HTML files
* Webpack Provider Plugin for providing jQuery & popper js to Bootstrap
* Glob for matching HTML files

## Getting Started

### Requirements
* Please make sure you have NodeJS installed, as this contains `npm`, which is necessary
for installing dependencies, starting the appropriate scripts, and building your web project.

### Quick Start
Clone the repo:

    git clone https://github.com/shaminmeerankutty/webpack-sass-bootstrap-boilerplate.git

Navigate to the project folder:

    cd webpack-sass-bootstrap-boilerplate

Install all packages and dependencies required for this project:

    npm install
    
Start the development environment (then, navigate to http://localhost:8080):

    npm start
 
Then, open a browser and navigate to: http://localhost:8080/ 
    
Building files can be done as follows:

    npm run build

### How To Use
* Add your HTML files by inserting or including them in the `src` directory (By default `index.html` is added to your `src` directory, feel free to edit it and 
experiment with the changes live.)
    
    * Make sure you restart development server after adding new HTML files

* Add images to your `src/assets` folder.
* Add sass (SCSS) files to `src/scss` folder.
  * Make sure you import the scss file in `main.scss` 
    
```sass
    @import "filename";
```

# Licence
Code released under the [MIT License](LICENSE.md).
