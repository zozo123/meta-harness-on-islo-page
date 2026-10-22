# meta-harness-on-islo-page

Project page for **Meta-harness on Islo**, a deterministic offline simulation of a harness optimization loop. A Python agent stand-in and a predefined task-hint proposer move five toy tasks from **0/5 to 5/5 in four steps**. These are simulation results, not a real-LLM benchmark. The Islo backend is an illustrative, unvalidated stub.

> **Live page:** https://zozo123.github.io/meta-harness-on-islo-page/
>
> **Code repo:** https://github.com/zozo123/meta-harness-on-islo
>
> **Proposed runtime integration:** [islo.dev](https://islo.dev/)

## Layout

```
index.html              site (single page, Bulma + custom CSS)
static/
  css/                  Bulma + bulma-carousel/slider + fontawesome (from template)
  js/                   carousel/slider scripts (from template)
  images/
    architecture.png    optimization-loop diagram
    bar-chart.png       deterministic simulation pass-rate per iteration
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
