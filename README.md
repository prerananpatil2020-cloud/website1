# DailyBlog (website1)

A minimalist, professional single-page static site for short daily blog posts.

Quick preview
 - Open `index.html` in your browser (double-click or serve with a static server).

What this contains
- `index.html` — main site: hero, featured post, post cards, search and tag filters, subscribe form placeholder.
- `style.css` — responsive, minimalist styles with subtle shadows and accent color.

Features
- Clean, accessible HTML structure and simple client-side search and tag filtering.
- Responsive layout that adapts to mobile and desktop.
- Minimal, professional visual design for quick reading.

How to use
1. Edit or add posts directly in `index.html` (each post is an `<article class="post">`).
2. Customize colors and spacing in `style.css` variables (see `:root`).
3. To serve locally with a simple HTTP server (optional), run from the project folder:

```powershell
# from Windows PowerShell
python -m http.server 8000
```

Then visit http://localhost:8000 in your browser.

Customization ideas
- Replace the static posts with a small CMS, Markdown build step, or client-side JSON feed.
- Add a dark theme variant by toggling `:root` variables or using a `data-theme` attribute.

License & contact
- No license specified. Add a `LICENSE` file if you want to declare reuse terms.
- Questions or edits: update files directly in this folder.
