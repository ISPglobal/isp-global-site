[README.md](https://github.com/user-attachments/files/23154441/README.md)
# ISP Global Inc — Static Site

Live: https://ispglobal.github.io/isp-global-site

## Local edits
Edit HTML files directly and commit. GitHub Pages auto-redeploys from `main` → `(root)`.

## Dark mode
Pages respect `localStorage['isp-theme']`. The `<html>` element gets a `.dark` class when theme is dark.

## Forms
Use a hosted form backend (Formspree/Basin/Netlify). `quote.html` can redirect to `thank-you.html` via hidden `_redirect` input.
