[![N|ketchup](http://tobiasfrei.ch/github/ketchup-starterkit/ketchup-starterkit-logo-01.svg)](https://tobiasfrei.ch)

# Ketchup Webpack Starterkit
Ketchup is a webpack boilerplate for developing static HTML pages with Nunjucks templates, ES201X transpiler and Sass precompiling with SVG sprites. Features precommit hooks with husky for csscomb, custom modernizr and autofix linting.

## Prerequisite
Node 10.11.0

## 1. Install Node.js
MacOS/Linux
```
https://github.com/creationix/nvm
```

Windows
```
https://github.com/coreybutler/nvm-windows
```

## 2. Install setup
Load node.js version
```
nvm use
```

Install Packages
```
npm install
```

## 3. Run setup
Run watcher
```
npm run dev
```

Run production
```
npm run prod
```

### Sprites
Inline
```
<svg viewBox="0 0 100 100" class="icon icon-arrow">
    <use xlink:href="#sprite-arrow"></use>
</svg>
```

### Authors
Tobias Frei, Christian Sany
