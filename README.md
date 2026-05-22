[README.md](https://github.com/user-attachments/files/28158314/README.md)
# Modern Blinds &amp; Shades — Site Concept

A single-page concept site, ready to deploy via GitHub Pages.

## Deploy

1. Create a new GitHub repo (any name, e.g. `modern-blinds-concept`).
2. Drop these files at the root of the repo:
   ```
   index.html
   README.md
   assets/
   ```
3. In repo **Settings → Pages**, set source to `main` branch, root folder. Save.
4. Site goes live at `https://<your-username>.github.io/<repo-name>/` in a minute or two.

That's the whole deployment story. No build step, no dependencies, no Node, no Hugo, no Webpack — just static files and a CDN.

## What's in here

```
index.html                              # the whole site, one file
assets/
  logo.png                              # Jake's existing logo (from the current site)
  hero.jpg                              # hero image — beach-house valances
  work-1.jpg                            # work band feature — cellular blue velvet
  work-2-placeholder.jpg                # placeholder, will be replaced
  work-3-placeholder.jpg                # placeholder, will be replaced
  designers-placeholder.jpg             # placeholder, will be replaced
```

## What's real, what's placeholder

**Real (keepable):**
- The two main photos (`hero.jpg` and `work-1.jpg`) are high-resolution architectural photography. Acceptable to ship with, ideal to replace with Jake's own projects when available.
- Jake's logo, palette, typography, and overall system.
- The voice and copy structure.

**Placeholder (must replace before launch):**
- Anything tagged `PLACEHOLDER` in the corner of an image (the small photos in the Work band and the For Designers section).
- All project captions ("Lake Minnetonka, 2024", etc.) — these are fictional.
- The note from Jake (`"I started this business because…"`) — needs his actual words.
- All mall addresses — best-guess from public info; Jake should verify.
- The email `jake@modernblindsandshades.com` is invented; the phone number was on the existing site but should be confirmed.

## Editing

The whole site is one HTML file with inline CSS. To change anything:

- **Colors** — see `:root` variables at the top of the `<style>` block. Change them once, everywhere updates.
- **Fonts** — Fraunces (serif) and Manrope (sans) are loaded from Google Fonts. To swap, change the `<link>` tag in `<head>` and the `--serif` / `--sans` variables.
- **Hero image** — replace `assets/hero.jpg` with any 1920×1080 (or larger) photo. Keep it as `hero.jpg` or update the `background-image` URL in the `.hero` CSS rule.
- **Headline copy** — `Designed in your home. Made for your light.` lives inside `<h1>` in the `.hero` section. The `<em>` tag handles the italic line break.
- **Sections** — every section has a comment block (`<!-- HERO -->`, `<!-- THE WORK -->`, etc.) for quick navigation.

## Browser support

Modern browsers (Chrome, Safari, Firefox, Edge — last two versions). Internet Explorer is not supported, and you don't need it to be.

## Next steps

The most leveraged next step is photography. A half-day shoot with an architectural photographer at one or two of Jake's recent installations would replace every `PLACEHOLDER` here and unlock the rest of the system. See the concept deck (slide 11) for the shot list.
