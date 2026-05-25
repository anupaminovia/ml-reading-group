# Inovia Machine Learning Reading Group

Inovia's weekly ML Reading Group! Join us for fun, high-level tutorials on the ML ecosystem from experienced researchers and developers in industry and academia, as well as discussion on future outlooks of ML. Our guest list features folks from across the ML stack, from FPGA design to virtual cell foundation models, providing for a holistic learning experience.

## Website

This repo also hosts a small static site for the reading group, served via **GitHub Pages**.

- `index.html` — landing page
- `schedule.html` — upcoming & past sessions
- `resources.html` — curated papers and primers
- `assets/css/styles.css` — styling

### Local preview

Any static file server works. For example:

```bash
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

### Deploying to GitHub Pages

1. Push to `main`.
2. In the repo settings → **Pages**, set **Source** to `Deploy from a branch`, **Branch** to `main`, and **Folder** to `/ (root)`.
3. GitHub will publish the site at `https://<owner>.github.io/ml-reading-group/`.

A `.nojekyll` file is included so GitHub Pages serves the HTML/CSS as-is without running Jekyll.

## Contributing

PRs welcome — propose topics for upcoming sessions, add notes/slides under a future `resources/` directory, or improve the site itself.
