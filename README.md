# Karad Sindhi Samaj website

A small, responsive HTML and CSS website for the Sindhi community in Karad. The site intentionally uses a plain layout, no stock photos, and a small amount of JavaScript for the mobile menu.

## Preview locally

Open `index.html` in a browser, or run a local static server from the repository root:

```sh
python3 -m http.server 8000
```

Then visit <http://localhost:8000>.

## Make updates

- **Page text and links:** edit `index.html`.
- **Layout and colors:** edit `assets/css/style.css`.
- **Mobile navigation:** edit `assets/js/main.js`.
- **Add community photos:** upload approved image files to `uploads/` and link to them from the page if needed. No external or stock images are currently used.
- **Rules, regulations, minutes, and albums:** add the approved PDF, Google Sheets, or Google Photos URL to the relevant resource row in `index.html`. Replace the “Link to be added” text with an anchor, for example: `<a href="YOUR_APPROVED_URL">Open document</a>`. For external links, use `target="_blank"` and `rel="noopener noreferrer"` if a new tab is desired.

Only publish information and photos that the Samaj has approved for public sharing. Get permission before publishing identifiable photos, especially photos of children. Do not publish private contact details or sensitive meeting information.

## GitHub Pages

This repository is named `karad-sindhi-samaj.github.io`, so it can be published from the `main` branch at the repository root. Check **Settings → Pages** to confirm the publishing source.
