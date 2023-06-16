
# JS Minify

Library user - https://cdn.skypack.dev/terser@latest

# CSS Minify

Generating plain JS module from node module.

```bash
mkdir x && cd x
npm install clean-css
npm install browserify -g
browserify -r clean-css -s CleanCSS -o clean-css.js
```

## Add "export default CleanCSS" at end of file

```
<script type="module">
    import CleanCSS from "./clean-css.js";
</script>
```

# HTML Minify

Related thread - https://stackoverflow.com/questions/65343130/html-minifier-in-client-side

# More Resources

- https://stackoverflow.com/questions/49562978/how-to-use-npm-modules-in-browser-is-possible-to-use-them-even-in-local-pc
- https://stackoverflow.com/questions/28674652/what-is-the-difference-between-browserify-requirejs-modules-and-es6-modules
- https://jspm.org/cdn/jspm-dev
- https://stackoverflow.com/questions/5168451/javascript-require-on-client-side