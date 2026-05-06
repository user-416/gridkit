# GridKit — public site

Marketing landing, privacy policy, terms of service, and support docs for the
[GridKit](https://user-416.github.io/gridkit/) iOS app.

The app source lives in a private repository. This repo holds only the
public-facing static site.

## Structure

```
.
├── index.html        ← landing
├── privacy.html      ← privacy policy
├── terms.html        ← terms of service
├── support.html      ← support / FAQ
├── styles.css        ← shared styles (dark-mode aware)
├── favicon.svg
├── robots.txt
├── sitemap.xml
└── .github/workflows/pages.yml   ← deploys to GitHub Pages on push to main
```

## Local preview

```sh
python3 -m http.server 8000
# open http://localhost:8000
```

## Deploy

Push to `main`. The Pages workflow takes ~30 seconds to publish. Live at
<https://user-416.github.io/gridkit/>.

## License

Site copy © 2026 Tony Gao. The HTML structure / CSS is MIT-licensed for your
reference, but please don't lift the privacy / terms wording verbatim — write
your own based on what your app actually does.
