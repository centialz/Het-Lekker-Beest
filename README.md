# Het Lekker Beest — website

A simple, fast website for the butcher shop & caterer **Het Lekker Beest**.
Built with plain HTML, CSS and JavaScript — no framework, no build step.

## Files

- `index.html` — the page structure and all sections.
- `styles.css` — all styling and responsive/mobile rules.
- `script.js` — language switcher (NL / FR / EN), mobile menu, and the reviews.

## Languages

Dutch is the default. Visitors can switch to French or English with the
NL / FR / EN buttons in the top menu. All text lives in the `I18N` object at
the top of `script.js` — edit the text there to change any wording.

## Things to replace (currently placeholder)

Search for the word **Placeholder** in `script.js` (the `contact_*` entries):

- Address
- Phone number (also update the `tel:` link in `index.html`)
- Email (also update the `mailto:` link in `index.html`)
- Opening hours

The reviews in `script.js` are the real Google reviews you provided.

## Deploy on Vercel

This is a static site, so no configuration is needed:

1. Push these files to a Git repository (or upload the folder).
2. In Vercel, create a new project from that repository.
3. Framework preset: **Other**. Leave the build command empty and set the
   output directory to the project root.
4. Deploy.

That's it — Vercel will serve `index.html` directly.
