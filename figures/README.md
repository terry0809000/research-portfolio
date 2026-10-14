# Research constellation

[Illustrated mind map](selected-projects-cosmos.png) · [Editable SVG](selected-projects-cosmos.svg) · [Mermaid source](selected-projects.mmd) · [Plain Mermaid preview](selected-projects-mermaid.png)

The illustrated version uses a generated raster background with separately editable SVG text, project links and connectors. All 12 project names are also available as Markdown text in the repository README.

## Rebuild the illustrated map

Install Node.js and Sharp in a local working copy, then run:

```sh
npm install --no-save sharp
node figures/render-mindmap.cjs
```

`selected-projects.json` supplies the labels. `health-ai-cosmos.png` is the background. The script writes the SVG and a 2400 × 1600 PNG.

The background was generated with the built-in image_gen tool; its prompt is recorded in `image-generation-prompt.txt`. It is conceptual artwork and contains no experimental results.
