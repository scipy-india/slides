# slides

Talks by the SciPy India community — [scipy-india.github.io/slides](https://scipy-india.github.io/slides).

Each talk is a self-contained Slidev project. `scripts/build-all.js` builds them all and generates the landing page.

## Dev

**Working on a talk:**
```bash
cd pyconf-hyd-community-partner-showcase-03-2026
npm install && npm run dev   # localhost:3030
```

**Previewing the landing page** (no dev server at root — build and serve):
```bash
npm run build:local && npx serve dist
```

`build:local` sets `BASE_PATH=/` so links resolve on localhost.

## Adding a talk

Folder name pattern: `{event}-{topic}-MM-YYYY` — e.g. `pyconf-hyd-community-partner-showcase-03-2026`.

Needs a `package.json` and a `slides.md` with at least `title:` in the frontmatter. Build script picks it up automatically.

## Structure

```
landing/
  style.css     # shared scipy-india stylesheet → copied to dist/
  styles.css    # landing-specific supplement, injected inline
  index.html    # template
scripts/
  build-all.js
SciPy-intro-slides.pdf   # copied to dist/ at build time
```
