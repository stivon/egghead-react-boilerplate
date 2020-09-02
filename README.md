# MODERN JAVASCRIPT TOOLING WITH REACT

## npm init

## GIT INIT

## NPM INIT -Y

## INSTALL WEBPACK AND WEBPACK-CLI

### node_modules/.bin/webpack

### node dist/main.js

### in package.json add : "build": "webpack" and then type npm run build in the terminal

### In development, you can use : npm run build -- --mode development

## Define an Entry Point with a webpack Configuration File

### webpack.config.js

## control the output of webpack wkth the mode setting : mode: 'development'

### we can let it with mode: production and use : npm run build -- --mode development

## Transform Modern Javscript features with Babel

### npm i -D @babel/core @babel/cli @babel/preset-env

## Configure webpack to Load JavaScript Files through Babel with babel-loader

### npm i -D babel-loader

## Configure Babel for React with preset-react

### npm i -S react react-dom prop-types

### npm i -D @babel/preset-react

## Inject a JavaScript bundle into HTML with the HtmlWebpackPlugin

### npm i -D html-webpack-plugin

## Update your bundle with Each File Save with Webpack's watch mode

### "dev": "webpack --watch --mode development"

## Create separate webpack configs for development and production

### npm i -D webpack-merge

### update webpack.config.js to webpack.config.base.js and add two files : webpack.config.dev.js and webpack.config.dev.js

## Serve a webpack Bundle while Developing with webpack-dev-server

### npm i -D webpack-dev-server

### we can change package.json to configure build et dev

### we can added a new port in webpack.config.development

## Generate source Maps for a better Debugging

### debugger

### Support Proposed JAvscript Features with Babel Plugins

### npm i -D @babel/plugin-proposal-class-properties

### Added an another key in webpack.config.base : plugins: ['@babel/plugin-proposal-class-properties']
