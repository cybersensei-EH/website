# CyberSensei-EH

Marketing website for **CyberSensei-EH** — an ethical hacking and cybersecurity training academy. "Master the Hack."

## Stack

Static HTML, CSS, and vanilla JS — no build step required.

```
index.html
css/styles.css
js/script.js
assets/img/
```

## Running locally

Serve the folder with any static file server, for example:

```
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Deploying

Any static host works (GitHub Pages, Netlify, Vercel, Cloudflare Pages). For GitHub Pages: enable Pages on this repo pointing at the root of the default branch.

## Things to customize

- **Founder photos** — `assets/img/founder-samuel.svg` and `assets/img/founder-reuben.svg` are placeholder initials cards. Replace them with real photos (e.g. `founder-samuel.jpg` / `founder-reuben.jpg`) and update the `src` attributes in `index.html`.
- **Contact details** — email, phone, and social links in the Contact section and footer of `index.html` are placeholders.
- **Contact form** — `js/script.js` currently only shows a confirmation message. Wire it up to a form backend (e.g. Formspree, a serverless function) to actually receive submissions.
- **Brand colors** — defined as CSS custom properties at the top of `css/styles.css` (`--primary`, `--secondary`, etc.) if you want to fine-tune the palette.
