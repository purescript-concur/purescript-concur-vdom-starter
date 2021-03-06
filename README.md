# Purescript Concur VDom Starter

A Starter kit for Purescript-Concur-VDom. Uses Npm, Spago, Google Closure Compiler, and Parcel. Builds tiny 60KB uncompressed bundles!

## Usage

### Grab the code

> git clone https://github.com/purescript-concur/purescript-concur-vdom-starter.git

Don't forget to tweak the project name and other details in package.json and bower.json

### Build code

> npm install

> npm run dev

### Run Dev Server

> npm start

## Hot code reload with purescript code

At the end of the previous command, you will have a development server
which will watch for changes, and automatically reload the web page.
This mechanism only works with JS changes.

However, in practice, your IDE should automatically recompile Purescript to
Javascript on every change, which will be picked up by the development server.
So you get immediate recompilation even with Purescript.

### Build production artifacts

> npm run prod
