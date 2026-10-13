# TaskFlow Board

Local Kanban work board with priorities, status transitions, filtering, and persistence.

**Live application:** https://sp-taskflow.vercel.app  
**Technology:** HTML, CSS, JavaScript  
**Visual direction:** Playful pastel Kanban workspace  
**Source:** https://github.com/sharanyapal/sp-taskflow

## Implemented functionality

- Create Kanban work items
- Move cards across stages
- Local storage persistence and filters

## Run locally

```bash
python -m http.server 8000
# Open http://localhost:8000
```

No build step or account required.

## Project structure

- `index.html` — semantic interactive application page
- `style.css` — independent responsive art direction and components
- `app.js` — application logic and input handling
- `app-base.js` — local browser utilities

## Safety and scope

A working portfolio-scale app, not a production security service. Local-only browser computation unless otherwise explained. No credentials are included.
