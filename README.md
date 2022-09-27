# Marp Themes

## How to add the themes

1. Create a folder for working and open the folder in VS Code.
2. Put `purdue-theme.css` and purdue-theme_.css into the created folder. This will add the themes: purdue-theme and purdue-theme_.
3. In the `markdown.md` file add the `purdue-theme` as follows:
``` yaml
---
marp: true
theme: purdue-theme
---
# Hello, world!
```
4. In VS hit `ctrl+,` and look for `markdown.marp.themes`. Once there, you can add a local path to the `*.css` files or a url.
