
# Reproduction for [typedoc-plugin-rename-defaults#17](https://github.com/felipecrs/typedoc-plugin-rename-defaults/issues/17)

Library code in ./src

Docusaurus website in ./website

## Running

```bash
npm i
cd website
npm i
npm start
```

You'll see that the "API" section in the sidebar is missing.

Modify & save any file in ./website to trigger a rebuild and restore the "API" section in the sidebar
