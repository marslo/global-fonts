## [marslo ( ubuntu )](https://userstyles.world/style/5264/marslo-ubuntu)

## some features
### gerrit comments

- `background: #083750` : for [solarized color style](https://ethanschoonover.com/solarized/)
- `background: #303030` : for dark background
- `background: #3a122e` : for ubuntu style background

```css
gr-linked-text[class*="pre"],
.gr-formatted-text-0 gr-linked-text.pre.gr-formatted-text,
gr-linked-text[class*="pre"] #output {
  font-family: "Monaco", "Menlo", "Andale Mono", "Ubuntu Mono", "monofur", "Consolas" !important;
  color: #eee !important;
  background: #083750 !important;                 /* solarized style */
  /* background: #303030 !important; */           /* dark background */
  border-radius: .75em !important;
  box-shadow: 0 4px 8px 0 rgb(0 0 0 / 20%), 0 6px 20px 0 rgb(0 0 0 / 19%);
  overflow: auto;
  display: block;
  padding: 8px;
  margin: -5px;
}
```

- result
  - ubuntu
    ![ubuntu](./screenshots/gerrit-comments-ubuntu.png)

  - solarized
    ![solarized](./screenshots/gerrit-comments-solarized.png)

  - dark
    ![dark](./screenshots/gerrit-comments-dark.png)
