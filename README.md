# 算法映像 · AlgoVista

Interactive algorithm tutorials that connect visual intuition, array indices, and C++ implementation. Organized in a sidebar by topic and subtopic.

**Live website:** https://thesatchel.github.io/algorithm-learning-tutorials/

## Current tutorial

**Matrix transformations — Luogu P1205 / USACO Transformations**

Located under **Arrays → Two-dimensional arrays**, with separate navigable **0-base** and **1-base** demonstrations. Index labels, formulas, loop bounds, and concrete array accesses update together. The 1-base demo shows the unused row and column at index 0.

- Animated clockwise rotation and horizontal reflection.
- Step-by-step copying from the original matrix into the destination matrix.
- Synchronized loop counters, index calculations, and highlighted cells.
- Playback, pause, single-step execution, and adjustable animation speed.
- Responsive desktop and mobile layouts.

The tutorial interface is in Chinese. The repository name and project documentation are in English.

## Run locally

This is a static website with no build step or external dependencies.

```sh
python3 -m http.server 8773
```

Open http://127.0.0.1:8773/ in your browser. You can also open `index.html` directly.

## Deployment

GitHub Pages publishes the root of the `main` branch. Push changes to `main` to update the website.
