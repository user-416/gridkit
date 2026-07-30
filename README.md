# Widgets public site

Landing page, privacy policy, terms of service, and support docs for the
[Widgets](https://user-416.github.io/widgets-site/) iOS app. Widgets is a small app
that shows daily numbers as a GitHub style contribution graph on your home
screen.

## Structure

```
.
├── index.html        landing
├── privacy.html      privacy policy
├── terms.html        terms of service
├── support.html      support / FAQ
├── styles.css        shared styles (dark-mode aware)
├── favicon.svg
├── robots.txt
├── sitemap.xml
└── .github/workflows/pages.yml   deploys to GitHub Pages on push to main
```

## Local preview

```sh
python3 -m http.server 8000
# open http://localhost:8000
```

## Deploy

Push to `main`. The Pages workflow takes about 30 seconds to publish. Live at
<https://user-416.github.io/widgets-site/>.

## License

Code (HTML/CSS/JS) is [MIT](LICENSE). Site copy is © 2026 Tony Gao. Please
don't lift the privacy or terms wording verbatim. Write your own based on what
your app actually does.
