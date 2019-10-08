# Getting Started

This repo was largely inspired and based on the starter bootstrap template [here](https://github.com/BlackrockDigital/startbootstrap-agency)


## Prerequisites

The following software should be installed on your machine and able to run in your terminal/command line:
- Git
  - Running `git --version` should return your installed git version
- Node.js and npm (Node Package Manager)
  - Running `node -v` should return your installed node.js version
  - Running `npm -v` should return your installed npm version

## Installation / Setup

- Clone this repo: `git clone https://github.com/andrewleonard1693/HomeDrone360.git`
- Install node dependencies: `npm install`
- Execute the gulp tasks: `./node_modules/gulp/bin/gulp.js`
  - This will pull dependencies out of the node_modules directory and minify/optimize our js and css files for faster loading times
  - For more information on what each gulp task does, check out the README in the parent bootstrap starter template [here](https://github.com/BlackrockDigital/startbootstrap-agency)

## Directory Structure

#### vendor

Contains css/js dependencies

#### scss

Contains SASS files that gulp compiles down to vanilla css when the `gulp` command is run

#### js

Contains our js files (and their minified versions) for client side logic

#### css 

Contains our css files (and their minified versions)

#### img

Contains images used on the client side