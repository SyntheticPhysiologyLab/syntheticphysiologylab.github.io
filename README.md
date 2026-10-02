# syntheticphysiologylab.github.io

This repository is the GitHub Pages site for [https://syntheticphysiologylab.github.io/](https://syntheticphysiologylab.github.io/). It redirects every path to the live lab site, [https://syntheticphysiologylab.com/](https://syntheticphysiologylab.com/).

GitHub Pages serves static files and cannot send a custom HTTP 301 to another origin. Each published HTML page is therefore a redirect document:

- `<meta http-equiv="refresh" content="0; url=…">` for browsers and crawlers that do not run JavaScript
- `location.replace` so the query string and hash are kept
- `<link rel="canonical">` pointing at the same path on the live site

`404.html` covers paths that are not generated from this repo. GitHub Pages keeps the requested URL when it serves that file, and the script forwards `pathname`, `search`, and `hash`. With JavaScript disabled, an unknown path falls back to the live site root.

Keep Pages enabled and publishing from this repository. Do not add a `CNAME` for `syntheticphysiologylab.com` or `www.syntheticphysiologylab.com`; the apex site is hosted elsewhere, and a `CNAME` here would stop `github.io` from serving the redirect.

## Check locally

```bash
bundle install
bundle exec jekyll serve
```

Then open `/`, `/team/`, and a path that does not exist. Each one should land on the same path at `https://syntheticphysiologylab.com/`.
