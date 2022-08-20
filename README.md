# Check version node / npm

- node -v
- npm -v

## Create package.json

- npm init

- package name: (setup_bs_sass)
- version: (1.0.0)
- description: Set up starter with bs5 with sass
- entry point: (index.js)
- test command:
- git repository:
- keywords: bootstrap5 sass
- author: TanNguyen

## install dependencies

- npm i sass --save-dev
- npm i bootstrap --save
- npm i @fortawesome/fontawesome-free --save
- npm i postcss-cli autoprefixer --save
- npm i animate.css --save

## Remove a dependency

- npm uninstall --save-dev package-name

## run a script

- "compile:sass": "sass scss:assets/css" => run this first to create folder assets/css
- "compile:sass": "sass --watch scss:assets/css" => then add --watch to compile everytime
- npm run compile:sass

## Tải dependency

- npm i
