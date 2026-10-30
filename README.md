# Cheng Liang — Academic Homepage

A static academic homepage adapted from [Jon Barron’s website](https://github.com/jonbarron/jonbarron.github.io).

- `index.html`: biography, research interests, and papers grouped into Looped Language Model Pretraining & Foundation Models and AI for Science, with resource links.
- `stylesheet.css`: original template typography and link styling.
- `site.css`: page layout and responsive styles.
- `assets/portrait.jpg`: profile photo.
- `data/Cheng_Liang_CV.pdf`: Chinese CV.

## Preview

Run `python3 -m http.server 8000` in this directory, then open http://localhost:8000.

## Deployment

GitHub Pages serves `main` from the repository root. Pushing to `main` automatically publishes updates at https://liangchengbupt.github.io/chengliang/.

Publication statuses, abbreviated author lists, and descriptions follow the supplied CV. Unreleased work has no placeholder resource links. Update this page when full author lists or public resources become available.

## Method figures

Figures are exported from the corresponding paper projects at 1600px resolution. Clicking a thumbnail opens the complete figure.

- AsymLoop: `Figure/asymloop-architecture-v2.pdf`
- UpLoop: `build/figures/fig3-method.pdf`
- RecLoop: `figures/architecture/architecture_v4.pdf`
- ChestX-Reasoner: `figures/method.pdf`
- PhenoLIP: `858/Latex_Source_File/figs/pipeline.pdf`

Additional figures from the CV project's `ref/` directory:

- Intern-S2-Mobius: `arXiv-2608.14290v1/assets/architecture.pdf`
- Balancing the Experts: `moe-balance-iclr26.jpg`
- LLM-Explorer: `arXiv-2505.10593v1/figure/overview.png`
- AVI-Bench: `arXiv-2606.07643v1/media/avi_pipe.png`

- MedSP1000: official repository `MAGIC-AI4Med/MedSP1000`, `assets/framework.png`.
