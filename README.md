# Ben Harvey — WordPress Consultant (GitHub Pages site)

This is a minimal single-page Jekyll site meant for publishing via GitHub Pages.

Files added:
- `index.html` — landing page content
- `_config.yml` — basic Jekyll metadata
- `assets/css/style.css` — page styles

Quick publish steps:

1. Push this repository to GitHub under `benwebdevleic/wordpress-consultant` (or your username/repo).
2. In the repository settings -> Pages, set the source to `main` branch, root (`/`). GitHub Pages will publish the site.

Local preview (optional):

Install Ruby and Jekyll (macOS Homebrew):

```bash
brew install ruby
gem install jekyll bundler
bundle install
jekyll serve --livereload
```

Note: Replace `ben@yourdomain.com` in `index.html` and `_config.yml` with your real email, or configure a form service like Formspree/Getform for a hosted contact form.

Want changes?
- I can add a contact form (Formspree/Getform), analytics, or a simple CMS preview.
