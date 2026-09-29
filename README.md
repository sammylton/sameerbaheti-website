# sameerbaheti-website

Personal portfolio for [sameerbaheti.com](https://sameerbaheti.com), built with plain HTML, CSS, and JavaScript for GitHub Pages.

## Local preview

From this directory, run one of these commands:

```bash
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

## Formspree setup

1. Create a form at [formspree.io](https://formspree.io/).
2. Copy the form endpoint.
3. Replace `REPLACE_WITH_YOUR_FORM_ID` in `index.html`.
4. Submit a test message after deploying.

## GitHub Pages and domains

Enable Pages from the repository's `main` branch and `/ (root)` folder. Add `sameerbaheti.com` as the custom domain in repository settings. At Namecheap, point the root domain to GitHub Pages using the current GitHub Pages A records and point `www` to the GitHub Pages CNAME. Configure `sameerbahetihq.com` as a forwarding/301 redirect to `https://sameerbaheti.com`.

The exact GitHub IP addresses can change, so use GitHub's current Pages documentation when configuring DNS.
