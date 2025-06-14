# Simple NodeJS package

```bash
npm install https://github.com/NdagiStanley/md_js_pkg
```

THEN

```js
import "md"
```

OR

```html
<script src="node_modules/md/index.js"></script>
```

with the following being a snippet of the `package.json`. Use either one. The gist referred to below is [this one](https://gist.github.com/NdagiStanley/e8aaecb67b11a8353bf16eb608b1a62d).

```package.json
...
"dependencies": {
  "md": "github:NdagiStanley/md_js_pkg",
  "md": "github:gist/e8aaecb67b11a8353bf16eb608b1a62d",
}
...
```
