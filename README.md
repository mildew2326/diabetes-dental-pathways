# Diabetes & Dental Health — Executive Briefing

An executive presentation synthesizing **peer-reviewed evidence** and **molecular pathways** linking diabetes mellitus and periodontal disease.

**Live deck:** open [`index.html`](./index.html) in a browser (or GitHub Pages once enabled).

## What's inside

| File | Purpose |
|------|---------|
| `index.html` | 8-slide executive presentation (keyboard / touch / button navigation) |
| `content/summary.md` | Source research summary (plain text / markdown) |
| `README.md` | This file |

## Presentation controls

- **Next / Prev** buttons
- Keyboard: `→` `←` `Space` `PageUp` `PageDown` `Home` `End`
- Swipe on touch devices
- Print to PDF via browser print dialog

## Evidence pipeline

Assembled with Hermes Agent MCP servers:

- **PubMed** — reviews, consensus statements, mechanistic papers
- **BioContextAI** — KEGG, Reactome, Open Targets, related biomedical APIs
- **UniProt** — protein context for pathway genes

### Pathway maps referenced

- KEGG `hsa04933` — AGE-RAGE signaling in diabetic complications
- KEGG `hsa04930` — Type II diabetes mellitus
- Reactome `R-HSA-879415` — Advanced glycosylation endproduct receptor signaling
- Open Targets disease `MONDO_0005148` — type 2 diabetes mellitus

## Key takeaways

1. Diabetes and periodontitis form a **bidirectional inflammatory loop**.
2. Periodontal therapy is associated with an average **~0.43% HbA1c reduction**.
3. Shared biology hubs: **AGE–RAGE → NF-κB**, innate immunity, bone remodeling.
4. Care systems should **co-screen and co-manage** dental and metabolic risk.

## Local preview

```bash
# Option A — open directly
xdg-open index.html   # Linux
open index.html       # macOS

# Option B — static server
python3 -m http.server 8765
# then visit http://127.0.0.1:8765
```

## GitHub Pages

If Pages is enabled for this repo (Settings → Pages → Deploy from branch `main` / root), the deck will be available at:

`https://<user>.github.io/diabetes-dental-pathways/`

## Disclaimer

This repository is for **executive communication and education**. It is **not medical advice**. Clinical decisions must follow current guidelines and licensed practitioners.

## License

MIT
