# Navanso host-ready submission

## Recommended thesis link

Submit the direct website:

`index.html`

Why: it opens directly on the functional MVP, so the jury sees the product first instead of a presentation wrapper. The MVP demonstrates the real loop: teacher dashboard, session entry, student follow-up, report generation, parent report, messages, and payments.

## Secondary link

Keep this available as a guided demo:

`walkthrough.html`

Use it during the defense if you want a narrated path, but do not make it the only submitted link. A walkthrough proves the story; the direct website proves the product.

## Hosting

Deploy the contents of this folder as a static site. The root URL should serve `index.html`.

Good options:

- Netlify Drop: drag the `navanso-host-ready` folder.
- GitHub Pages: publish this folder as the static site root.
- Any static host: upload `index.html`, `walkthrough.html`, and `assets/`.

After hosting, test these paths:

- `/` opens the MVP.
- `/walkthrough.html` opens the guided tour.
- `/index.html#dashboard` opens the teacher dashboard.
- `/index.html#parent-report/r-yacine-mai-2026` opens the parent report.

