
# Sass Example

## Build

Requirement: [Node.js](https://nodejs.org/) and its included package manager, *npm*

*Install dependencies*

```sh
npm install
```

*Compile Sass to CSS, and minify the result*

```sh
npm run build
```

*Compile with source maps*

```sh
npm run build:dev
```

*Watch for file changes and compile with source maps automatically*

```sh
npm run watch
```

## Source maps

Source maps allow mapping the compiled CSS to its source Sass files when using a browser's inspector. This makes development easier by showing which file corresponds to an element's style.

An example is included in this repository. Open *index.html* in a browser, and see that the inspected style shows its source file and line number.

## Style guide

See: [Sass Guide](https://github.com/eliot-akira/sass-guide)

## References

[How to Use npm as a Build Tool](https://github.com/keithamus/npm-scripts-example)
