# Punch List

Shared, live punch list / workplan for the Health Sciences comp project: This week, Focus, Departments, Grant review, Archive, and TV Mode.

- Single static file: `index.html`. No build step.
- Backend: Supabase (anon key in the page; RLS is the gate. Currently open to anyone with the link).
- Identity: name prompt on first visit, stored in the browser.

## Hosting (GitHub Pages)

Settings → Pages → Source: *Deploy from a branch* → `main` / `(root)`.
The page is then served at `https://thill-ships.github.io/uhealth-strategy/punch-list/`.
