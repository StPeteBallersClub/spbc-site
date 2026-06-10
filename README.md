# St. Pete Ballers Club — Website

A complete 6-page site in the SPBC black/gold identity: **Home, Events, Membership, Shop, Partners, About/Join.**

## Files
- `index.html` — Home
- `events.html` — Tournaments, leagues, weekly pickup
- `membership.html` — Founders Club ($15/mo or $99/yr founding)
- `shop.html` — SPBC + SPVB apparel
- `partners.html` — Sponsor pitch + sponsorship inquiry form
- `about.html` — Story, values, how to join + JOIN form
- `styles.css` — Shared design system (do not delete; every page uses it)
- `spbc-logo.png` — Your gold crest, used in the nav, footer, and home hero (keep it in the same folder as the HTML files when you deploy)

---

## STEP 1 — Connect the two forms (Formspree)

There are two forms. Each needs its own Formspree endpoint.

1. Go to formspree.io, sign up / log in with **stpeteballersclub@gmail.com**
2. Create **two** forms: name one "SPBC Join" and one "SPBC Sponsor"
3. Each gives you an endpoint like `https://formspree.io/f/abcd1234`
4. Paste them in:
   - **about.html** — find `YOUR_JOIN_FORM_ID`, replace the whole URL with your Join endpoint
   - **partners.html** — find `YOUR_SPONSOR_FORM_ID`, replace with your Sponsor endpoint
5. Submit each form once yourself to confirm it arrives in the Gmail inbox (Formspree asks you to verify the first time)

---

## STEP 2 — Drop in your real links

Search each file for `#` placeholder links and `href="#"` and replace:

- **membership.html** — the two "Join" buttons and the bottom CTA → your Wix Pricing Plans / Stripe checkout link(s)
- **shop.html** — "Visit the Store" button → your Wix store URL
- **events.html** — the Summer Showdown button already points to your Volleyball Life link; update for future events

---

## STEP 3 — Put it online

**Option A — GitHub Pages (free, what you've used before):**
1. Create a new repo, upload all files (keep them in the same folder, `styles.css` alongside the HTML)
2. Settings → Pages → deploy from `main` branch, root
3. Point your domain (stpeteballers.com) at it via your domain registrar's DNS

**Option B — Recreate in Wix:**
Use these pages as the exact design/copy blueprint and rebuild in the Wix editor so memberships, store, and site all live under one roof.

---

## IMPORTANT — One domain, not two

You own both stpeteballers.com and stpeteballersclub.com. Pick ONE as primary
(recommend stpeteballers.com) and set the other to **redirect** to it. Running two
live sites splits your traffic and doubles maintenance.

---

## Notes on accuracy
- Stats shown: 3,380 IG followers, 736 community members, 6-hour sellout. Update these as they change — they appear on the Home and Partners pages.
- Membership pricing ($15/mo, $99/yr founding → $120) reflects the launch plan. Adjust if it changed.
- The Partners page is your media-kit-on-the-web. Add real engagement rate + audience demographics from Instagram Insights when you have them — that's what closes sponsor deals.
