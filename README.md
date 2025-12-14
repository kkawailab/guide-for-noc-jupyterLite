# Nature of Code (JupyterLite notebooks)

This folder contains chapter-by-chapter summaries of Daniel Shiffman's *The Nature of Code* with tiny runnable examples tailored for a JupyterLite (Pyodide) environment.

## Structure
- `notebooks/ch00-introduction.ipynb` to `ch10-neural-networks.ipynb` — one notebook per chapter
- Each notebook opens with a short markdown recap and a single self-contained Python example (no external packages)

## How to use in JupyterLite
1. Upload or place the `notebooks/` directory in your JupyterLite workspace.
2. Open any chapter notebook and run cells in order. They avoid heavy dependencies so they should run out of the box.
3. Tweak the parameters listed under "Try:" in the first cell to explore each topic further.

## Notes
- Examples are minimal text-based demonstrations so they stay portable inside JupyterLite.
- For richer visuals, you can replace the placeholder vector/physics code with p5-like drawing once available in your environment.
