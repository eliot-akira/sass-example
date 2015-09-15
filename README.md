
## Sass example

### Build

Requirement: [Node.js](https://nodejs.org/) and its included package manager, *npm*

*Install dependencies*

```sh
npm install
```

*Compile Sass to CSS, and minify the result*

```sh
npm run build
```

*Compile with sourcemaps*

```sh
npm run build:dev
```

*Watch for file changes and compile with sourcemaps automatically*

```sh
npm run watch
```

---

### Source maps

Source maps allow mapping the compiled CSS to its source Sass files, when using a browser's inspector.

An example is included in this repository. Open *index.html* in a browser, and see that the inspected styles indicate the correct source file and line number.

---

Also see [Sass Guide](https://github.com/eliot-akira/sass-guide).
