# DITO MOBILE — Premium Preview (Standalone)

**Technical project slug:** `dito-mobile-premium-preview-2026-11-02`  
**Visible app brand:** DITO MOBILE  
**Purpose:** isolated UI prototype for review only.

## Important separation rules
- This is a NEW, standalone preview project.
- It is NOT the original `a0-s/dito-mobile-app` repository.
- Do not rename this folder/repository to `dito-mobile-app`.
- Do not merge this project into `main`, `dev-services`, or any existing DITO repository.
- Do not copy, replace, or migrate Supabase schemas, credentials, storage, authentication, or user data.
- If the design is approved, selectively port the UI into the original project after comparing its current components and preserving its backend.

## Preview
This is a static website. Open `index.html` in a browser, or publish this folder as a separate GitHub Pages site.

## GitHub Pages deployment (separate repository)
1. Create a NEW repository named exactly `dito-mobile-premium-preview-2026-11-02`.
2. Upload the contents of this folder to its root (especially `index.html`).
3. In that new repository, open Settings → Pages.
4. Choose deployment from the `main` branch and `/ (root)`, then save.
5. Use only the Pages URL generated for this new repository for previewing.

## Included interactions
- Responsive dark monochrome premium UI
- Arabic/English language toggle
- Home, explore, profile, settings, messages, notifications, and login screens
- Mobile bottom navigation and desktop sidebar
- Interactive like/save demo and creation sheet

## Not connected
Authentication, Supabase, database, uploads, camera/gallery permissions, messaging, notifications, and live streaming are visual placeholders only.
