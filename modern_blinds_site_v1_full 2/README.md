# Modern Blinds &amp; Shades — Site Concept (V1: Existing Logo)

A 7-page concept site, ready to deploy via GitHub Pages.

## What's in here

```
index.html                              # home page
work.html                               # featured work
how-we-work.html                        # process detail
for-designers.html                      # trade program
about.html                              # Jake's story
visit-us.html                           # three locations
contact.html                            # contact form
style.css                               # shared stylesheet for all pages
README.md                               # this file
assets/
  hero.jpg, work-1.jpg, logo.png        # real photos + logo
```

## Deploy

1. Create a new GitHub repo.
2. Drop everything from this folder at the **root** of the repo.
3. Settings → Pages → Source: `main` branch, root folder. Save.
4. Live in ~1 minute at `https://<username>.github.io/<repo>/`.

## What's real, what's placeholder

**Real:**
- The two main photos (`hero.jpg` on home + first featured project, `work-1.jpg` on home + second featured project)
- The brand system: palette, typography, layout, navigation
- Voice samples in the structural copy

**Placeholder (clearly marked with [PLACEHOLDER COPY] tags or "Photography in Progress" cards):**
- Project descriptions on the Work page
- Process narratives on How We Work
- Trade testimonials
- Jake's actual narrative on About
- All photo slots beyond the two real images

**Forms are not yet functional.** Both the trade application (on `for-designers.html`) and the contact form (on `contact.html`) need a backend service. Options:
- [Formspree](https://formspree.io) — free for low volume, drop-in HTML attribute
- [Basin](https://usebasin.com) — similar
- [Netlify Forms](https://www.netlify.com/products/forms/) — if you switch hosting to Netlify

Each form has a "Developer note" placeholder explaining this; remove it once the form is wired.

## Editing

All pages share `style.css`. To change a color, font, or spacing across the whole site, edit `style.css` once.

To change page-specific content (copy, photos), edit the individual HTML file. Each page is self-contained with the same header and footer markup at top and bottom.

To swap a photo: replace the file in `assets/` keeping the same filename. To add a new photo, drop it in `assets/` and reference it as `assets/your-file.jpg` in the HTML.

## Browser support

Modern browsers (Chrome, Safari, Firefox, Edge — last two versions).

## Next steps

Same as before: **photography is the gate**. Every page above gets stronger with real project photos. The shoot fills every `PLACEHOLDER` here.

After that, Jake's writing — three pages (Home, About, How We Work) have narrative copy that needs to come from him directly.
