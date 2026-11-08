# acupressa — Acupressure legal pages

Static site for GitHub Pages hosting the legal documents of the **Acupressure** app.

## Pages

| Page | File | URL |
| --- | --- | --- |
| Overview | `index.html` | https://andarg.github.io/ |
| Privacy Policy | `privacy-policy.html` | https://andarg.github.io/privacy-policy.html |
| Your Privacy Rights | `privacy-rights.html` | https://andarg.github.io/privacy-rights.html |
| User Agreement | `user-agreement.html` | https://andarg.github.io/user-agreement.html |

For AppGallery submission use:

- **Privacy policy URL** — `https://andarg.github.io/privacy-policy.html`
- **Privacy rights URL** — `https://andarg.github.io/privacy-rights.html`
- **User agreement / Terms of Service URL** — `https://andarg.github.io/user-agreement.html`

## Publish

1. Push to `main` of `git@github.com:andarg/andarg.github.io.git`.
2. Repository **Settings → Pages → Source: Deploy from a branch → `main` / `/ (root)`**.
3. Wait for the deployment, then check that all four URLs open over HTTPS.

## Before publishing

Contact address used on the pages: `tsaritov@gmail.com` (in `privacy-policy.html`,
`privacy-rights.html` and `user-agreement.html`). Update the “Last updated” dates if the texts are edited.

## Structure

```
.
├── index.html
├── privacy-policy.html
├── privacy-rights.html
├── user-agreement.html
├── assets/style.css
├── .nojekyll
└── README.md
```

No build step — plain HTML/CSS, responsive, light/dark aware.