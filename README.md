# Process.io — marketing site

Professionell SaaS-landningssida för **Process.io**, rekryterings-OS:et (produktens app = RecruitFlow).
En självständig statisk sida — ren HTML/CSS/JS i `index.html`, inga beroenden, inget byggsteg.

## Innehåll
- Hero med produktmockup
- **Interaktiv demo** (direkt under hero): AI-sourcing-sök, copilot-Q&A, animerad datapipeline
- Statistik, funktioner, "så funkar det"
- **3 prisnivåer** (Starter / Growth / Enterprise) med månad/år-toggle och tydlig ✓/✕-jämförelse
- CTA + footer

## Kör lokalt
```bash
python -m http.server 5455
# → http://localhost:5455
```

## Deploy (Render)
Statisk sajt — `render.yaml` finns. Skapa en **Static Site** på render.com kopplad till repot
(Publish directory `.`, ingen build). SPA-rewriten `/* → /index.html` är harmlös/robust.
