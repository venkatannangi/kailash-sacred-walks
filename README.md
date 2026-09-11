# Kailash Sacred Walks Foundation — website

Static site, no build step, no server code.

## Files
- `index.html` — the whole site (HTML, CSS, JS in one file; pages are switched by URL hash: #home, #seva, #annadanam, #yatra, #projects, #videos, #newsletter, #donate)
- `images/logo.png` — hero logo (transparent background)
- `images/logo-small.png` — header logo

## Hosting
Upload the folder to any static host (cPanel public_html, Netlify, GitHub Pages, Cloudflare Pages). Keep `index.html` and `images/` together.

## Before going live
1. `REG_EMAIL` in the script at the bottom of index.html — set to the foundation's email (the yatra registration form opens a prefilled email to this address). Swap for a Google Form / Formspree action if a stored inbox is preferred.
2. Donate page (#donate) — replace the "to be added" placeholders (bank/UPI/PayPal, email, WhatsApp).
3. Photo slots — the dashed grey boxes in `.gallery` divs on Annadanam, Yatra and Projects pages; replace each `<div>` with an `<img>`.
4. Newsletter issues — each `<article class="issue" id="issue-YYYY-MM">`; copy the block to add an issue. Share/Copy buttons work from the id.
5. External dependencies: Google Fonts (Cormorant Garamond, Source Sans 3, Noto Serif Tamil, Noto Serif Devanagari) and YouTube embeds.
