KARST LAB HOMEPAGE — CACHE-BUSTED SCALE FIX

The previous update used the same filenames, so your browser/GitHub Pages could keep serving
the cached CSS and hero image. This version deliberately uses NEW filenames so the changes
must load.

Visible changes:
- Hero text is noticeably smaller.
- "From early-life signals to lifelong health" is smaller.
- Hero height is reduced.
- Research card image areas/headings are slightly smaller.
- The hero artwork uses a wider source crop and is fit with object-fit: contain, preserving
  the microbiota on the left and the outcome labels on the right.

UPLOAD / REPLACE:
1. Replace index.html
2. Add home-v2.css
3. Add assets/home-hero-illustration-v2.jpg

You can leave home.css and home-hero-illustration.jpg in the repo; the new index no longer
references them. After GitHub Pages updates, a normal refresh should show the new version.
