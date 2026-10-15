# Track2Map project page

This folder contains the static GitHub Pages project page for Track2Map.

## Local preview

From the repository root:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## GitHub Pages deployment

In the GitHub repository settings:

1. Go to `Settings` → `Pages`.
2. Set `Source` to `Deploy from a branch`.
3. Select branch `main` and folder `/ (root)`.
4. Save.

The project page URL is:

```text
https://track2map.github.io/
```

## Publication links

The page tracks the published version of the paper:

- `Paper` button → Springer, MICCAI 2026 proceedings (LNCS), DOI `10.1007/978-3-032-38236-8_52`.
- `arXiv` button → preprint `arXiv:2607.08408`.
- The BibTeX block in `index.html` cites the published Springer version (pages 542–552).
