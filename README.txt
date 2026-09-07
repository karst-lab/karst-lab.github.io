KARST LAB HOMEPAGE — GUARANTEED INLINE FIX

Why this version is different:
The previous CSS-only updates were apparently not being reflected reliably on the live page.
This version puts the critical sizing and hero-fit rules directly inside index.html, AFTER the
external stylesheets. That means these rules cannot be missed because of an old CSS file being
cached or uploaded incorrectly.

Visible changes:
- Smaller "Karst Laboratory"
- Smaller hero statement and supporting copy
- Smaller "From early-life signals to lifelong health"
- Shorter hero
- Clean illustration-only hero image
- Full left and right sides of the hero illustration preserved with object-fit: contain

UPLOAD / REPLACE EXACTLY:
1. Replace index.html
2. Add/replace assets/home-hero-illustration-v3.jpg

That is all. You do not need to change home.css for this test.
