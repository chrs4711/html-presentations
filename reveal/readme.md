The [docs](https://revealjs.com/installation/) say to just clone the repo:

```
git clone https://github.com/hakimel/reveal.js.git
```

## Custom style

Take the [custom style](custom-style/chracula.scss) and copy it to the styles folder of reveal:

```
cp custom-style/chracula.scss reveal.js/css/theme/source
```

build revealjs

```
npm build
```

The custom style can now be used like this:

```html
<link rel="stylesheet" href="reveal.js/dist/theme/chracula.css">
```

