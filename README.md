[README.md](https://github.com/user-attachments/files/27150555/README.md)
# Lacy Graduates! · UNO Class of 2026

A personal graduation celebration website built as a single self-contained HTML file, designed to be hosted on GitHub Pages. Built for Lacy's graduation from the University of Nebraska Omaha on May 8, 2026.

---

## Hosting on GitHub Pages

1. Rename `lacy_graduation.html` to `index.html`
2. Create a new GitHub repository (can be public or private — Pages requires public on free accounts)
3. Push `index.html` and this `README.md` to the `main` branch
4. Go to **Settings → Pages**, set source to `main` branch, root folder
5. Your site will be live at `https://yourusername.github.io/your-repo-name`

The file is entirely self-contained — all images are base64-encoded inside the HTML, so no additional assets are needed.

---

## What's Inside

### Tabs

| Tab | Theme | Music |
|---|---|---|
| 🏠 Home | UNO (black/red) | *School's Out* — Alice Cooper |
| 📷 Photos | KKΨ (blue/gold) | *Good Riddance* — Green Day |
| Thank You | UNO (black/red) | *Thank You for Being a Friend* — Andrew Gold |
| Joining From Afar | KKΨ (blue/gold) | *I Lived* — OneRepublic |
| Joining In Person | UNO (black/red) | *KKΨ Fraternal Hymn* |

### Features

- **Live countdown** to 3:00 PM CT, May 8, 2026 at Baxter Arena
- **Alternating tab themes** — UNO colors (black, red, grey) and KKΨ colors (royal blue, gold, white)
- **Auto-playing music** per tab on first interaction, with a floating mute button
- **Photo gallery** with lightbox viewer (click any photo, arrow keys to navigate, Escape to close)
- **Collapsible itinerary days** on the Joining In Person tab
- **Clickable links** throughout — Google Maps for every location, websites for every restaurant and attraction
- **UNO and KKΨ branding** used throughout as subtle background watermarks per KKΨ brand standards (clearspace respected, no unauthorized outlines or boxes)

### Pages in Detail

**Home** — Hero with graduation photo background, UNO "O" logo, live countdown, tagline

**Photos** — Masonry grid of college photos with full lightbox. NatCon photo featured full-width at top.

**Thank You** — Editorial rows with alternating UNO bull / UNO "O" icons, name in large serif type, personal blurbs. Photo placeholders ready to swap in real photos.

**Joining From Afar** — Message to remote guests, livestream link placeholder, follow-along schedule, Venmo/Cash App/mailing address for gifts, Google Form guestbook link placeholder

**Joining In Person** — Full 5-day itinerary (May 7–11) with collapsible days, restaurant cards with menus and directions

---

## Things to Update Before Sharing

### Required
- [ ] **Livestream link** — Replace the UNO Commencement Info button URL with the actual stream link once UNO posts it (usually 1–2 weeks before graduation)
- [ ] **Guestbook** — Create a Google Form and replace `YOUR_GOOGLE_FORM_LINK_HERE` with your form's share URL

### Optional
- [ ] **Thank You photos** — Replace the bull/O icons in the Thank You tab with actual photos of each person. Each circle is `110×110px`, `border-radius: 50%`. Swap the `src` of each `<img>` inside `.ty-circle`
- [ ] **Flight origin airports** — The itinerary shows arrival times but not origin cities; add those to the Day 1 timeline entries if desired

---

## Branding Notes

### University of Nebraska Omaha
- Colors: Black `#1a1a1a`, Red `#d00000`
- Logos used: Interlocking "O", Maverick bull

### Kappa Kappa Psi
- Colors: Royal Blue `#09268a` (RGB 9, 38, 138), Gold `#ffc61e` (RGB 255, 198, 30)
- Crest: Used with ¼-width clearspace on all sides, no border or box per brand standards
- Wordmark: Used with K-height clearspace on all sides per brand standards

---

## Technical Notes

- **Single file** — ~2.6MB, all assets embedded as base64
- **No dependencies** — no frameworks, no build step, no CDN required
- **No backend** — works entirely in the browser; the guestbook uses an embedded Google Form
- **Music** — streams from Internet Archive on tab switch; falls back silently if blocked. Users can mute with the floating button (bottom right)
- **Browser support** — modern browsers (Chrome, Firefox, Safari, Edge). Audio autoplay requires a user interaction first per browser policy.

---

*Made with love for Lacy — UNO Class of 2026. Musicianship · Leadership · Service.*
