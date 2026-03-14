# SciPy India: Building Scientific Community in India

**Talk:** PyConf Hyderabad 2026 · Community Partners
**Speakers:** Srihari Thyagarajan & Agriya Khetarpal

## Context

Community talk covering SciPy India's revival arc: from the first online community
call in July 2025 through 4 community calls, the joint SciPy India × BangPypers
offline meetup in February 2026, and what's coming next (FOSSHack 2026, annual
conference planning).

Original deck: `../LaTeX-existing-slides/` (IndiaFOSS 2025, FOSS in Science Devroom).

## Theme

Uses Slidev's built-in `default` theme (not `seriph`). Reasons:

- `seriph`'s serif/academic aesthetic matched the original Beamer presentation style
  but is the wrong register for a community-momentum talk
- `default` is lighter, more approachable — fits the tone of "here's what we built together"
- SciPy blue (`#0073B7`) applied via `styles/custom.css` maintains brand identity
  without the academic weight

## Human Review Checklist

Before presenting, verify:

- [ ] Quote on slide 11 is verbatim from the BangPypers meetup blog post
- [ ] QR code (`public/qr-code.png`) still resolves to the intended destination
- [ ] All external links on slides 12–13 are live
- [ ] CC#2 and CC#3 dates — not pinned in this deck; add if known
- [ ] GitHub issue #17 link for conference planning is still accurate

## Dev

```bash
npm install
npm run dev      # localhost:3030
npm run build    # static build
npm run export   # PDF export (requires playwright-chromium)
```
