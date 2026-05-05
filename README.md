# islo-sandbox-based-meta-harnessing-demo

Project page for **Meta-harness on Islo** — a 200-line POC that wires the [meta-harness](https://yoonholee.com/meta-harness/) optimization loop onto Islo sandboxes.

> **Live page:** https://zozo123.github.io/islo-sandbox-based-meta-harnessing-demo/
>
> **Code repo:** https://github.com/zozo123/meta-harness-eng-islo

## Layout

```
index.html              site (single page, Bulma + custom CSS)
static/
  css/                  Bulma + bulma-carousel/slider + fontawesome (from template)
  js/                   carousel/slider scripts (from template)
  images/
    architecture.png    optimization-loop diagram
    bar-chart.png       pass-rate per iteration
    heatmap.png         task × iteration grid
    dashboard-sketch.png  layout sketch of viz/index.html
    favicon.ico
  pdfs/
    paper.pdf           docs/post.pdf from the code repo (typeset writeup)
```

## Local preview

```bash
python3 -m http.server 8000
# open http://localhost:8000/
```

## Built from

[`eliahuhorwitz/Academic-project-page-template`](https://github.com/eliahuhorwitz/Academic-project-page-template) — the Nerfies-style academic project page template. CSS/JS dependencies are kept; content and layout were rewritten for this project.

## License

MIT — © 2026 Yossi Eliaz.
