# Blue Ridge Resilience

Static cybersecurity publication / portfolio starter for Cloudflare Pages.

## Local preview

From this folder:

```bash
python3 -m http.server 8080
```

Then visit http://localhost:8080

## Cloudflare Pages deployment

1. Create a GitHub repository and push this folder to `main`.
2. In Cloudflare: Workers & Pages -> Create application -> Pages -> Import an existing Git repository.
3. Select the repository.
4. Production branch: `main`.
5. Framework preset: None.
6. Build command: `exit 0` (or leave blank if Cloudflare allows it).
7. Build output directory: `public`.
8. Deploy.
9. Add your custom domain under the Pages project's Custom domains section.

## Editing

- `public/index.html` = home page
- `public/blog/index.html` = article index
- `public/projects/index.html` = projects page
- `public/styles.css` = site-wide colors/layout
- Add new articles inside `public/blog/` and link them from `blog/index.html` and the home page.

## Suggested next upgrade

Move articles to Astro/Markdown once publishing frequency increases. This static version intentionally has no package dependencies and is extremely easy to deploy.
