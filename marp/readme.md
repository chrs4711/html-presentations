Type some text in a markdown file, then:

```
npx @marp-team/marp-cli@latest slides.md
```

it will yield `slides.html`

### PDF output

... can be achieved with:

```
npx @marp-team/marp-cli@latest slides.md --pdf
```

### with css

```
marp --theme ./dracula.css 
```