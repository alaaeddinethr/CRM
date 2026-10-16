# SIEFER Trigonal: Prospecting CRM

Lightweight CRM built for the SIEFER TRIGONAL® Maroc sales team to run B2B prospecting: companies, contacts, a drag-and-drop deal pipeline and an activity history, in one browser page.

**Live app:** https://alaaeddinethr.github.io/CRM/

## Features

- Dashboard with pipeline value and activity at a glance
- Prospects and companies with search and filters
- Kanban pipeline: drag deals between stages
- Activity history and settings
- Keyboard-first navigation: command palette with `Ctrl + K`
- Data stored in the browser (`localStorage`), so no account and no server are needed

## Limitations

- Data stays in the browser it was entered in: there is no sync between users or devices, and clearing the browser data erases it. Export regularly or move to a shared backend for team use.
- The *Emails & AI* tab drafts outreach emails through the Anthropic API. It only works where an API proxy provides authentication; on this static page it is disabled, and no API key is stored in the code.

## Run it

Open `index.html` in a browser, or use the live link above. No build, no dependency.

Sample records are placeholders for demonstration.

---

Built by Alaa Eddine Tahir for the [SIEFER TRIGONAL® Maroc](https://github.com/alaaeddinethr/SIEFER-TRIGONAL) sales team · [LinkedIn](https://linkedin.com/in/alaaeddine-tahir)
