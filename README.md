# SDDF 2027 — Saudi Digestive Diseases Forum

**Brand:** Saudi Gastroenterology Association (SGA) / MM Group  
**Purpose:** Official congress website — 8-page multi-page HTML site  
**Owner:** Khalid (Tech) / Hala (content)  
**Managed by:** Meeting Minds Experts (MM Group)  
**Repo:** mmgroup-sddf-2027  
**Live URL:** https://sddf2027.com *(pending domain setup)*  
**Last updated:** April 2026

---

## Site Structure

| File | Page |
|------|------|
| `index.html` | Home / Hero |
| `about.html` | About the Forum |
| `speakers.html` | Speakers & Faculty |
| `programme.html` | Scientific Programme |
| `registration.html` | Registration |
| `venue.html` | Venue & Travel |
| `sponsors.html` | Sponsorship & Exhibition |
| `contact.html` | Contact |

```
sddf-2027/
├── index.html
├── about.html
├── speakers.html
├── programme.html
├── registration.html
├── venue.html
├── sponsors.html
├── contact.html
├── assets/
│   ├── css/
│   │   └── style.css        ← shared stylesheet
│   └── js/
│       └── shared.js        ← nav, mobile menu, scroll reveal
├── .github/
│   └── workflows/
│       └── deploy.yml       ← GitHub Actions SSH deploy
└── README.md
```

---

## Design System

| Token | Value |
|-------|-------|
| Primary (Navy) | `#0E2240` |
| Accent (Gold) | `#C49A2A` |
| Gold Light | `#E0B84A` |
| Cream background | `#FAF7F0` |
| Display font | Cormorant Garamond |
| Body font | Outfit |

---

## Deployment — GitHub Pages

**No server or domain required.** The site deploys automatically to GitHub Pages on every push to `main`.

### Live URL format:
```
https://[your-github-org].github.io/mmgroup-sddf-2027/
```

### One-time setup (do once after creating the repo):
1. Go to repo → **Settings → Pages**
2. Under **Source**, select **GitHub Actions**
3. Push to `main` — the Actions workflow deploys automatically

### No secrets needed.
GitHub Pages uses built-in `GITHUB_TOKEN` permissions defined in the workflow. No SSH keys or server credentials required.

### Deploy trigger:
Any push to `main` branch triggers automatic deployment. The live URL is shown in the Actions run log and in Settings → Pages.

---

## Logo Placeholder

The site currently uses an SVG silhouette mark as placeholder. Once SGA selects the final logo from Hala's three concepts (The Scope / The Loop / The Tract), replace:
1. The `.logo-mark svg` in each HTML file with the actual logo SVG or `<img>` tag
2. Update favicon

---

## Content Updates

All placeholder content (faculty TBC, venue TBC, prices) to be updated as SGA confirms:
- Scientific committee nominations
- Confirmed venue (Q4 2026)
- Faculty / speakers
- Hotel block details
- Final programme

---

## Contacts

| Role | Contact |
|------|---------|
| Tech owner | Khalid (MM Group) |
| Content owner | Hala (MM Group) |
| Client | Saudi Gastroenterology Association |
| PCO | Meeting Minds Experts |
