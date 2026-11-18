# Karad Sindhi Samaj website

A small, responsive website built with HTML, CSS, JavaScript, and GitHub Pages' Jekyll support. The common page structure is shared through Jekyll includes and a layout, so the header, navigation, and footer only need to be updated once.

## Shared page structure

- `_includes/header.html` contains the site header and navigation.
- `_includes/footer.html` contains the site footer.
- `_layouts/default.html` loads the shared header and footer around each page's content.
- `_config.yml` configures the GitHub Pages/Jekyll site.

To add a page, create a file such as `about.html`, start it with front matter, and write only the page-specific content below it:

```yaml
---
layout: default
title: About | Karad Sindhi Samaj
---
```

The shared header and footer will be included automatically when GitHub Pages builds the site. Navigation links can be changed in `_includes/header.html`.

## Preview locally

GitHub Pages builds the site with Jekyll. With Ruby and Bundler installed, run `bundle exec jekyll serve` if the GitHub Pages dependencies are installed. For a quick static preview, open the published site after pushing changes.

## Make updates

- **Page text and links:** edit `index.html` or a page-specific HTML file.
- **Shared header/navigation:** edit `_includes/header.html`.
- **Shared footer:** edit `_includes/footer.html`.
- **Layout and colors:** edit `assets/css/style.css`.
- **Mobile navigation:** edit `assets/js/main.js`.
- **Add community photos:** upload approved image files to `uploads/` and link to them from a page. No external or stock images are currently used.
- **Rules, regulations, minutes, and albums:** add approved PDF, Google Sheets, or Google Photos URLs to the relevant page.

Only publish information and photos approved for public sharing. Get permission before publishing identifiable photos, especially photos of children. Do not publish private contact details or sensitive meeting information.

## GitHub Pages

The repository is named `karad-sindhi-samaj.github.io`, so it can be published from the `main` branch at the repository root. Check **Settings → Pages** to confirm the publishing source.
