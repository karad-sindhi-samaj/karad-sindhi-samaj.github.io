# Karad Sindhi Samaj website

A responsive, HTML-first GitHub Pages website for the Sindhi community in Karad. The site uses plain HTML, CSS, and a small amount of JavaScript, with Markdown files for community documents and records.

## Preview locally

Open `index.html` in a browser, or run a local static server from the repository root:

```sh
python3 -m http.server 8000
```

Then visit <http://localhost:8000>.

## Update the site

- **Main page and navigation:** edit `index.html`.
- **Colors, layout, and responsive styles:** edit `assets/css/style.css`.
- **Mobile navigation and current-year footer:** edit `assets/js/main.js`.
- **Community guidelines:** update `content/community-guidelines.md` and the matching summary on the page.
- **Meeting records:** add approved, privacy-reviewed Markdown notes under `content/meeting-minutes/`.
- **Notices and gallery:** replace the empty noticeboard and illustrative stock photos in `index.html` with approved community updates and images. Obtain permission before publishing identifiable people, especially children.

The member/contact links are intentionally not connected yet. Add an official Samaj contact address before publishing contact details. Replace the illustrative photos with approved community photos when available. The current guidelines are draft principles and are not represented as formally adopted rules.

## GitHub Pages

This repository is named `karad-sindhi-samaj.github.io`, so it can be published as an organization/user site from the `main` branch at the repository root. In the repository, check **Settings → Pages** and select the `main` branch and `/ (root)` as the build source if Pages is not already configured.
