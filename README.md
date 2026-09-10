# HR Day · Session Invite — The Future of Work

Interactive HTML invitation for Misal Sir (guest speaker) for the SOIL HR Day 2026 session: **"The Future of Work: Skills, AI & the New Organisation"** (10:00–10:45 AM).

Built as a single self-contained `index.html` — no build step, no dependencies. Live on GitHub Pages.

## Interaction
- Session & speaker details cards
- **RSVP selector**: travel choice (cab / self-drive reimbursed) + deck preference
- Live countdown to session start (tomorrow 10:00 AM)
- Confirmation panel on submit

## Deploy
```bash
gh repo create soil-hrday-invite --public --source=. --push
gh api repos/<owner>/soil-hrday-invite/pages -X POST -f source[branch]=main -f source[path]=/
```
Live: `https://<owner>.github.io/soil-hrday-invite/`
