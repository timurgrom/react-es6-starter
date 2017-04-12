React ES6 Starter
==================

Features
----------

- Webpack 2
  - Transpiling JS using babel
  - Dynamic `index.html` generation
  - Dynamic build file names for cache busting
  - ESLint - Lints `js` files on changes. Rules at `.eslintrc`
  - Stylelint - Lints `scss` files on changes. Rules at `.stylelintrc`
  - Sass support
  - PostCSS plugins support. Settings at `postcss.config.js` (e.g. Autoprefixer)
  - HTML5 History API (non hash routes)
- React
  - React Hot Loader v3
  - React Router v4

Getting Started
----------------

1. Install Node.js
    - From [nodejs.org](https://nodejs.org/) (All platforms)
    - Or using [Homebrew](http://blog.teamtreehouse.com/install-node-js-npm-mac) (Mac)
    - Or any other [package manager](https://github.com/joyent/node/wiki/Installing-Node.js-via-package-manager)
1. Fork the repo and `git clone` it
1. Install dependencies (at the root of the repo):

    ```
    npm install
    ```

Development
------------

#### Run webpack-dev-server

```
npm start
```

- Open `http://localhost:8080`

Build the project for deployment
---------------------------------

```
npm run build
```

- Must use a server that redirects missing routes back to `index.html`

### To run locally

```
cd dist/
live-server --entry-file=index.html
```
