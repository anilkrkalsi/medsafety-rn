# MedSafety RN GitHub Pages replacement

Complete static replacement website for the existing repository:

`https://github.com/anilkrkalsi/medsafety-rn`

Target URL:

`https://anilkrkalsi.github.io/medsafety-rn/`

## Package contents

- Plain semantic `index.html`
- Responsive `styles.css`
- Official Google Play badge
- App icon and all eight screenshots retrieved from the public Google Play listing
- Optimized WebP screenshot assets
- 1200 × 630 Open Graph image
- Favicons and web manifest
- `robots.txt` and `sitemap.xml`
- SoftwareApplication JSON-LD

No `script.js` is included because the native HTML `<details>` and `<summary>` elements provide keyboard-accessible FAQ controls without JavaScript.

## Replace the existing GitHub Pages site

1. Extract `MedSafety_RN_GitHub_Pages_Final.zip` on your computer.
2. Open the existing `anilkrkalsi/medsafety-rn` repository. Do not create another repository.
3. Remove the old website files from the repository root, then upload the **contents** of the extracted folder so `index.html` remains at the repository root.
4. Commit the replacement files to the branch currently used by GitHub Pages, normally `main`.
5. In **Settings → Pages**, confirm that deployment still uses the same branch and `/ (root)` folder.
6. After GitHub finishes deployment, open `https://anilkrkalsi.github.io/medsafety-rn/` and hard-refresh the page.

## Important URLs

- Google Play: `https://play.google.com/store/apps/details?id=com.sadhoo.medsafety_rn`
- Privacy policy: `https://anilkrkalsi.github.io/medsafety-rn-privacy/`
- Support: `mailto:anilkrkalsi@gmail.com`

No build process, npm installation, external JavaScript framework, analytics, advertisements, cookies, trackers, contact form or external font is required.
