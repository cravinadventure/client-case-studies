# Client Case Studies — Cravin' Adventure Studios

The landing/menu page for Cravin' Adventure Studios client case studies. Organized by client (artist or brand): photo, name, Instagram, a short description, the projects done for them with dates, and a button into each client's full case-study page.

**Live:** https://cravinadventure.github.io/client-case-studies/

Self-contained static `index.html` (inline CSS) plus client photos in `assets/`. No build step.

## Adding a client

Copy the `<article class="cs-card">` block in `index.html`, swap the photo (drop into `assets/`), name, `cs-type` (DJ / Artist / Brand), `@handle`, description, the project rows (name + sub + date), and point the `cs-btn` at that client's `client-case-study-<djname>` page.

## Local preview

```
python3 -m http.server 4180 --directory .
```

Then open http://localhost:4180
