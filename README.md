# watagashi0619/marp-theme-academic

> this template is forked from [kaisugi/marp-theme-academic](https://github.com/kaisugi/marp-theme-academic), customized by watagashi0619

## Features

- change the design, including font size and colour scheme
- blue and red colorbox classes added to css (html rendering needs to be enabled)

## preview

instant preview is [here](https://watagashi0619.github.io/marp-theme-academic/demo.html)!

![](./demo.001.png)
![](./demo.002.png)
![](./demo.003.png)
![](./demo.004.png)
![](./demo.005.png)
![](./demo.006.png)
![](./demo.007.png)

## how to use

1. Install the Marp plugin in vscode.

2. Paste the following codes in you VS Code Settings(`settings.json`).

```json
  "markdown.marp.themes": [
    "https://raw.githubusercontent.com/watagashi0619/marp-theme-academic/main/themes/academic.css"
  ],
  "markdown.marp.enableHtml": true
```

## tips

- You can use javascript by adding a script tag to the beginning of the markdown file.
  - TikZJax
  - draw.io
  - mermaid
  - etc...
