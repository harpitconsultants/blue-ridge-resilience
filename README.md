# Blue Ridge Resilience — fixed site

Drop-in replacement for the current static Cloudflare site.

## Replace
Copy the contents of `public/` over the repository's existing `public/` folder.

Cloudflare settings:
- Framework preset: None
- Build command: exit 0
- Build output directory: public

The site uses one shared stylesheet (`/styles.css`) and one shared mobile-menu script (`/script.js`).
