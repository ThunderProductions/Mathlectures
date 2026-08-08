# Inequalities — Algebra 2

An interactive, scrollable lesson on inequalities, built as a single self-contained HTML file. Styled like a video player: scrub the top bar to jump between chapters.

**Covers:**
- Compound inequalities (AND / OR) — drag bounds, test any number live
- Quadratic inequalities — sign charts + a live parabola graph
- Systems of inequalities — toggle constraints and watch shaded regions overlap
- A 4-question self-check quiz

No build step, no dependencies beyond Google Fonts (loaded via CDN). Everything else is plain HTML/CSS/JS in `index.html`.

## View it locally

Just open `index.html` in any browser.

## Publish with GitHub Pages

1. Create a new repository on GitHub (e.g. `inequalities-lesson`).
2. Push these files to it:
   ```bash
   git init
   git add .
   git commit -m "Add interactive inequalities lesson"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<repo-name>.git
   git push -u origin main
   ```
3. On GitHub, go to **Settings → Pages**.
4. Under **Source**, choose the `main` branch and `/ (root)` folder, then save.
5. GitHub will publish it at `https://<your-username>.github.io/<repo-name>/` within a minute or two.

## License

MIT — see `LICENSE`.
