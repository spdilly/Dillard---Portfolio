# Sean Dillard Portfolio

Minimal dark-theme portfolio for GitHub Pages.

## Quick Deploy

1. Download and extract the ZIP
2. Go to https://github.com/spdilly/Dillard---Portfolio
3. Delete all existing files (backup if needed)
4. Upload ALL contents from the extracted folder:
   - `index.html`
   - `about.html`
   - `case-clearpath.html`
   - `case-pricing.html`
   - `assets/` folder (with all PDFs)
5. Enable GitHub Pages: Settings → Pages → Source: main branch
6. Wait 2-3 minutes, site live at: https://spdilly.github.io/Dillard---Portfolio/

## File Structure

```
/
├── index.html           # Homepage
├── about.html           # About page  
├── case-clearpath.html  # Behavioral health case
├── case-pricing.html    # Pricing case
└── assets/
    ├── SPD_Resume_2025.pdf
    ├── SPD_3S_Pricing_Analysis.pdf
    ├── Clearpath_FY1_Operating_Review.pdf
    ├── Clearpath_FY1_Operating_Review.pptx
    ├── clearpath_raw_data.xlsx
    └── Methodology_Behind_The_Scenes.pdf
```

## Design

- Dark theme (#09090b background)
- Green accent (#22c55e)
- Inter font
- All CSS is inline (no separate stylesheet = no path issues)
- Properly sized images via Unsplash with explicit dimensions
- Mobile responsive

## To Add a Photo

Replace the initials placeholder in `about.html`. Find:

```html
<div class="avatar">
  <span class="avatar-text">SD</span>
</div>
```

Replace with:

```html
<div class="avatar" style="padding:0;overflow:hidden">
  <img src="assets/headshot.jpg" alt="Sean Dillard" style="width:100%;height:100%;object-fit:cover">
</div>
```

Then upload your photo to the `assets/` folder.
