# webpack-sass-bootstrap-boilerplate
Sass, Babel &amp; Bootstrap boilerplate with Webpack building,Dev Server and Live Loading

## Features
* Webpack 4 bundling
* Babel ES6 Compiler
* Sass Compiler
* Bootstrap v4
* jQuery 3.3.1
* Popper.js 
* Webpack Dev Server

## Webpack Loaders
* Sass Loader for compiling sass
* File Loader for loading asset files
* Html Loader for loading html files
* Babel Loader for compiling ES6 code

## Webpack Plugins 
* Extract Text Plugin for extracting css files
* Clean Webpack Plugin for cleaning unwanted files in dist directory
* Html Webpack Plugin for generating html files
* Webpack Provider Plugin for providing jquery & popper js to bootstrap

# Requirements
* Please make sure you have node js installed

# Quick start

Clone the repo

    git clone https://github.com/shaminmeerankutty/webpack-sass-bootstrap-boilerplate.git

Install All Packages

    npm install
    
Starting Developement Environment (Check the browser at http://localhost:8080/)

    npm start
    
Building files

    npm run build

# How to use
* Add your html files in the `src` directory (By default `index.html` is added to your `src` directory, feel free to edit it)
  * Make sure you add it in your `webpack.config.js` (Replace `name` with your `filename`)
  
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

* Add images to your `src/assets` folder
* Add sass files to `src/scss` folder 
  * Make sure you import the scss file in `main.scss` 
    
    ```sass
    @import "filename";
    ```

# Licence
Code released under the [MIT License](https://github.com/shaminmeerankutty/webpack-sass-bootstrap-boilerplate/blob/master/LICENSE.md)


