# Lumen & Co. — Starter Site (Freelance Digital Marketing)

Same structure and deployment process as the Ridgeline example, just
re-themed for a freelance digital marketing business — different subject,
so it got a different design direction: a "campaign board" look (pinned tag
chips, index-card services) instead of the trades/blueprint look.

## What's in here

```
marketing-site/
├── index.html        <- all page content and structure
├── css/style.css      <- all styling
└── README.md          <- this file
```

## Deploying it (same process as before)

1. **Preview locally** — just open `index.html` in a browser.
2. **Push to GitHub:**
   ```bash
   cd marketing-site
   git init
   git add .
   git commit -m "Initial site"
   git remote add origin https://github.com/yourusername/lumen-site.git
   git branch -M main
   git push -u origin main
   ```
3. **Turn on GitHub Pages:** repo → Settings → Pages → Source: Deploy from a
   branch → `main` / `/(root)` → Save. Live in about a minute at
   `https://yourusername.github.io/lumen-site/`.
4. **Make the contact form real (optional):** sign up free at
   [formspree.io](https://formspree.io), grab your form endpoint, and swap it
   in for `your-form-id` in `index.html`.
5. **Every future change:** `git add . && git commit -m "..." && git push` —
   the live site updates automatically within a minute or two.

## What's different from the Ridgeline version

- **Colors:** warm putty paper, ink-plum text, coral/mustard/sage/blue accents
  (all defined as CSS variables at the top of `css/style.css` — easy to retheme).
- **Type:** Fraunces (a characterful serif) for headings instead of the bold
  grotesk used before — meant to feel more boutique/creative than industrial.
- **Signature element:** a scattered "campaign board" of pinned tag chips in
  the hero, instead of the work-order ticket cards — services shown as pinned
  notes rather than dispatch tickets, matching a strategist's workspace feel
  instead of a dispatch board.

Same underlying lesson either way: swap copy, colors, and structure, and this
becomes a real, deployable site for whichever business you're actually
building for.
