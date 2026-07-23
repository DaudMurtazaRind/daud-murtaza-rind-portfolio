# Daud Murtaza Rind Portfolio

Minimal static portfolio website built with pure HTML and Tailwind CSS via CDN.

## Files

- `index.html` - complete single-page website
- `assets/daud-murtaza-rind-portrait.jpg` - optimized portfolio portrait
- `assets/daud-murtaza-rind-social.png` - social sharing preview image
- `robots.txt` - search engine crawl instructions
- `sitemap.xml` - sitemap for search engines
- `README.md` - local run and deployment instructions

## Run locally

1. Open `index.html` directly in your browser.
2. Or serve the folder with a simple local server for a more realistic preview.

### PowerShell option

```powershell
cd "C:\Frontend Dev\daud-murtaza-rind-portfolio"
python -m http.server 8080
```

Then open `http://localhost:8080`.

## Deploy to GitHub Pages

1. Create a new GitHub repository.
2. Upload the contents of this folder.
3. Make sure `index.html` is in the repository root.
4. Keep `robots.txt` and `sitemap.xml` in the repository root as well.
5. In GitHub, open `Settings > Pages`.
6. Under `Build and deployment`, choose:
   - `Source`: `Deploy from a branch`
   - `Branch`: `main` and `/root`
7. Save the settings and wait for GitHub Pages to publish the site.
8. Expected site URL:

```text
https://daudmurtazarind.github.io/daud-murtaza-rind-portfolio/
```

## SEO notes

- The homepage includes a canonical URL, search description, Open Graph tags, and structured data.
- `robots.txt` points search engines to the sitemap.
- If you later use a custom domain, update the URL in `index.html`, `robots.txt`, and `sitemap.xml`.

## Customization

- Update text directly inside `index.html`.
- Change colors in the Tailwind config block near the top of the file.
- Replace contact links if needed:
  - Email: `mailto:daud21111987@gmail.com`
  - WhatsApp: `https://wa.me/923348965346`
