# Jenga PM — Legal Site

Static HTML site containing the Privacy Policy and Terms of Service for Jenga PM. Hosted separately from the main app.

## Structure

```
Jenga-Legal/
├── index.html      # Landing page with links to privacy and terms
├── privacy.html    # Privacy Policy
├── terms.html      # Terms of Service
├── favicon.png     # Favicon
└── icons/
    ├── favicon-light.png
    └── favicon-dark.png
```

## Styling

Inline CSS only — no build step, no dependencies.

| Property | Value |
|----------|-------|
| Background | `#1C140D` (Charcoal) |
| Text | `#EDEDED` |
| Headings & links | `#F28C26` (Safety Orange) |
| Font | Arial (system fallback) |
| Max width | 860px, centered |

## Deployment

No build step required — serve the files directly as static HTML. Any static host (GitHub Pages, Cloudflare Pages, Replit, Nginx) works.

## Updating Legal Documents

Edit `privacy.html` or `terms.html` directly. Always update the "Last updated" date at the top of the file when making substantive changes.

## Links From Other Repos

- **Web app:** `components/views/PrivacyPolicyView.tsx` and `components/views/TermsOfServiceView.tsx` render inline copies.
- **Mobile app:** `lib/screens/privacy_policy.dart` displays the legal content in-app.
- The canonical hosted versions (this repo) are linked from the app stores and Google OAuth consent screen.
