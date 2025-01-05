# emuxo-css

`emuxo-css` is a usability-focused CSS library.
`emuxo-css` is primarily used for [emuxo.com](https://emuxo.com), but can be used in any website.

See the [`emuxo-css` **demo/docs here**](https://nimjay.github.io/emuxo-css/).

To use `emuxo-css` in your own website, just copy over the file at [/docs/emuxo.css](https://github.com/EmuxoApp/emuxo-css/blob/main/docs/emuxo.css).
Alternatively, you could import the file from emuxoapp.github.io/emuxo-css/emuxo.css:
```
<link href="https://emuxoapp.github.io/emuxo-css/emuxo.css" rel="stylesheet" type="text/css">
```

## Develop on your machine

If you would like to make source code changes to `emuxo-css` (on your local machine), follow these steps:

1. Clone this repository.
```
git clone https://github.com/NimJay/emuxo-css.git
```

2. Move into the `src` folder.
```
cd emuxo-css/src
```

3. Download JavaScript/Node.js dependencies.
```
npm install
```

4. Start compiling the Stylus (.styl) files into CSS.
```
npm run compile-stylus
```

5. In a spearate terminal, serve the documentation (found inside `docs/`) by running the following from the `src` folder:
```
cd src
npm run serve-docs
```

## Questions? Bugs? Feature requests?

If you have questions, run into bugs, or have feature requests, create [a GitHub issue](https://github.com/NimJay/emuxo-css/issues/new). :)
