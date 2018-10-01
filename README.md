# webpack-sass-bootstrap-boilerplate

Sass, Babel & Bootstrap boilerplate with Webpack building, a Dev Server and Live Loading

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

### Check Out Our Documentation
If you want to check out our official documentation, just click [here](https://shaminmeerankutty.github.io/webpack-sass-bootstrap-boilerplate/).

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
  * Make sure you add it in your `webpack.config.js` as follows: 
  (Replace `name` with your `filename`)

```javascript
plugins: [
    ...
        new HtmlWebpackPlugin({
        template: 'src/name.html',
        inject: 'body',
        filename: 'name.html'
        }),
    ...
],
```

* Add images to your `src/assets` folder.
* Add sass (SCSS) files to `src/scss` folder.
  * Make sure you import the scss file in `main.scss` 
    
```sass
    @import "filename";
```

# Licence
Code released under the [MIT License](https://github.com/shaminmeerankutty/webpack-sass-bootstrap-boilerplate/blob/master/LICENSE.md).