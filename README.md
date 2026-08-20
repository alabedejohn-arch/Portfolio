[README.md](https://github.com/user-attachments/files/31278206/README.md)
# JayTechPremiumMedia — Website Package

This package contains everything needed to launch the JayTechPremiumMedia portfolio site, either by rebuilding it in Wix or hosting the HTML file directly.

## What's in this package

| File | Purpose |
|---|---|
| `index.html` | A complete, working version of the site — open it in any browser to preview. Use it as your visual reference, or host it as-is. |
| `John_Mercy_Portfolio_Site_Copy.md` | The Wix AI generation prompt, brand/contact reference sheet, and full page-by-page copy for rebuilding the site inside Wix. |
| `README.md` | This file. |

## Option A: Preview or host the HTML file directly

1. Double-click `index.html` to open it in your browser — no setup needed, it's fully self-contained.
2. To publish it as a live site, upload it to any static host (Netlify, Vercel, GitHub Pages, or your own hosting) and point your domain to it.
3. **Before going live:** the contact form doesn't send messages anywhere yet — it just shows a confirmation alert. Connect it to a form backend (e.g. Formspree, Netlify Forms) or replace it with a `mailto:` link if you're not using Wix.

## Option B: Rebuild in Wix

1. Open `John_Mercy_Portfolio_Site_Copy.md`.
2. Start a new site in Wix AI and paste in the **Part 1: Wix AI Generation Prompt** block when it asks what your site is about.
3. Use the **Part 2: Brand/Contact Reference Sheet** table for any setup fields Wix AI asks for individually (business name, email, socials).
4. Once Wix generates the site skeleton, go section by section and paste in the matching copy from **Part 3: Page-by-Page Copy**.
5. Use `index.html` open in your browser alongside the Wix editor as a layout reference — section order, spacing, and tone — even though Wix's design system will look different from the raw HTML.

## Logo usage

- **Header / navbar logo:** the horizontal wordmark (`channels4_banner.jpg` style) — reads clearly at header size.
- **Favicon / social profile picture:** the circular "JT" badge (`channels4_profile.jpg` style) — built for square avatar crops (YouTube, Instagram, TikTok, browser tab).
- The wordmark logo has a light, non-transparent background — ask for a transparent PNG version before dropping it into a dark header, or it'll show a visible white box.

## Brand reference

- **Site name:** JayTechPremiumMedia
- **Tagline:** Delivering Success With Every Solution
- **Colors:** Black `#0A0A0A`, White `#FAFAFA`, Red `#E4202C`
- **Fonts used in `index.html`:** Anton (headlines), Inter (body), JetBrains Mono (labels/eyebrows) — all loaded free via Google Fonts

## Still to do before launch

- [ ] Confirm exact site name formatting: "JayTechPremiumMedia" vs "Jay.Tech Premium Media" (logo uses the latter)
- [ ] Get a transparent-background version of the wordmark logo
- [ ] Add a real headshot photo (hero section currently uses the JT badge instead)
- [ ] Connect the contact form to a real backend (Wix does this automatically once rebuilt there)
- [ ] Swap in real Instagram/TikTok/YouTube content or embeds in the Work section
- [ ] Decide on a domain (e.g. jaytechpremiummedia.com) if not using a Wix subdomain
