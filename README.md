# Neighborhood Studios · Portfolio KPI Dashboard

Live: <https://kpi.neighborhoodstudios.com/>

Full-screen, always-on KPI wall for the Neighborhood Studios portfolio. One headline metric per operating company (Homegrown, Loop, Dandy, January, Zing), a horizontally-scrollable strip of live experiments, and a 10-week time-travel stepper. Behind a shared client-side password gate (soft, not real auth).

## Local preview

```
cd site
python3 -m http.server 8000
open http://localhost:8000/
```

Password: `localsonly` (all lowercase). Persists per-device in `localStorage`.

## Deploy

GitHub Pages from `main` (repo root). The `CNAME` file sets the custom domain. `.nojekyll` disables Jekyll processing.

## Stack

Vanilla HTML/CSS/JS. No build step. Design tokens live in `design-tokens/*.css`.
