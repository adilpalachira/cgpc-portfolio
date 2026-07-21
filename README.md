# Adil M — Personal Portfolio

A premium, handcrafted personal portfolio for Adil M, a full‑stack (MERN) developer based in Kerala, India. Built with plain HTML5 and CSS3 only — no frameworks, no JavaScript libraries.

## Folder structure

```
portfolio/
│
├── index.html
├── style.css
├── portrait.jpg
├── adil-m-resume.pdf
│
└── README.md
```

## Tech

- Semantic HTML5
- Modern CSS3 — Grid, Flexbox, custom properties, `clamp()`, `backdrop-filter`, gradients, keyframe animation
- Google Fonts: **Outfit** (display/body), **Caveat** (signature/handwriting), **Space Mono** (labels/eyebrows)
- Zero JavaScript, zero build step — open `index.html` directly in a browser

## Design tokens

| Token | Value |
|---|---|
| Background | `#F7F5F2` |
| Primary text | `#111111` |
| Accent | `#F4E409` |
| Dark sections | `#111111` |
| Secondary text | `#6B6B6B` |
| Cards (dark) | `#181818` |
| Borders | `rgba(0,0,0,0.08)` |

## Sections

1. **Navigation** — floating glass pill nav with hover‑underline links
2. **Hero** — asymmetric two‑column intro with a CSS‑only paper/portrait composition, brush‑stroke text highlight, circular rotating "Always Learning" stamp, and a floating glass badge
3. **Featured Work** — dark editorial grid of three real projects with CSS‑drawn UI previews
4. **About** — split layout with portrait, signature, and a detail list (education, email, location, GitHub, LinkedIn)
5. **Skills** — dark section with skill cards and a "What I Do" list over CSS abstract line art
6. **Contact** — large CTA, contact form, and direct contact links
7. **Footer** — minimal, with social links

## Editing content

- Swap `assets/images/portrait.jpg` for a different photo (same filename, or update the `src` in `index.html`).
- Replace `assets/adil-m-resume.pdf` to update the "Download Resume" link.
- All copy lives directly in `index.html` — no CMS or data file.

## Responsive breakpoints

- Desktop: default (max‑width 1440px content)
- Laptop: `≤1180px`
- Tablet: `≤960px`
- Mobile: `≤640px`
