# μ◬¹⁰ — Shronda Jeanine & Co. | Muse Healing Site (Jekyll)

Glassmorphic Jekyll site for Shronda Jeanine & Company. Ported from Next.js 15 to Jekyll for GitHub Pages native deployment.

**Live URL:** https://shrondaj.github.io/muse-healing-site/

## Brand

- **Tagline:** with purpose on purpose
- **Signature:** 72079 (July 20, 1979) — hidden throughout the design
- **Palette:** Mu Ink · Spark Gold · Healing Purple · Raw Canvas

## Structure

```
muse-healing-site/
├── _config.yml          # Site config, brand values, social links
├── _layouts/
│   ├── default.html     # Base layout (nav + footer + orbs)
│   └── post.html        # Blog post layout
├── _includes/
│   ├── head.html        # <head> meta + CSS link
│   ├── navigation.html  # Fixed glassmorphic nav
│   ├── footer.html      # Footer with socials + contact
│   └── muse-mark.html   # SVG logo mark (parameterized size)
├── _posts/              # 15 blog posts (Markdown)
├── _sass/
│   └── muse.scss        # Full design system
├── assets/
│   ├── css/main.scss    # Jekyll Sass entry point
│   └── js/navigation.js # Mobile menu JS
├── index.html           # Home page (hero, services, quiz CTA, about)
├── blog.html            # Blog listing with category filter
└── quiz.html            # 4-question interactive healing path quiz
```

## Local Development

```bash
bundle install
bundle exec jekyll serve --livereload
# → http://localhost:4000/muse-healing-site/
```

## Deploy

Push to `main` → GitHub Actions builds and deploys automatically.

## Adding Blog Posts

Create `_posts/YYYY-MM-DD-slug.md` with front matter:

```yaml
---
title: "Post Title"
description: "One-sentence excerpt shown on blog listing."
date: 2026-05-01
category: Healing
image: "https://..."
read_time: "5 min"
tags: [healing, practice]
---

Post body in Markdown...
```

## 72079 Concealed Signature

Hidden throughout the design:
- `line-height: 1.72079`
- `animation-duration: 7.2079s`
- `border-radius: 7.2079px`
- `z-index: 72079`
- `background: rgb(7, 20, 79)`
- `transition-delay: 0.079s`
- `letter-spacing: 0.079em`

Always purposeful. Always there. Never visible.
