# Bootstrap 5 Starter Template

This repo contains all the needed set up files and `package.json` file for creating a website using Bootstrap 5 with Sass and a free version of Font Awesome icons from the npm package `@fortawesome/fontawesome-free`.

After downloading zip file or cloning the repository, run the following commands to get setup and started compiling the `scss` files into `css` files:
```bash 
# To install all the needed npm packages
$ npm i # or npm install
```

```bash
# To build the css files; automatically creates css folder with files
$ npm run sass:build
```

```bash
# To watch and build files while developing
$ npm run sass:watch
```

With VS Code Live Server extension running, and running the terminal command `npm run sass:watch` the web page will automatically reload on each change to `scss` or `html` files.