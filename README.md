# site

Static placeholder for `surkov.company`, served by GitHub Pages from `master` (root).

- `index.html` — the page; no build step, no external requests.
- `CNAME` — the custom domain. DNS (`@` A/AAAA to GitHub Pages, `www` CNAME) lives in
  `infra/tofu` (`extra_records`).

Changes reach `master` only through a PR.
