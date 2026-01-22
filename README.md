# Sean Dillard Portfolio

A clean, professional FP&A portfolio site built for GitHub Pages.

## Quick Start

### Option 1: Replace Your Existing Repo

1. Go to your repo: https://github.com/spdilly/Dillard---Portfolio
2. Delete all existing files (or back them up first)
3. Upload all files from this folder
4. GitHub Pages will automatically rebuild

### Option 2: Fresh Setup

1. Create a new repo or use existing
2. Upload all files maintaining the folder structure
3. Enable GitHub Pages in Settings → Pages → Source: main branch

## File Structure

```
/
├── index.html              # Homepage with case study cards
├── about.html              # About page with experience
├── case-clearpath.html     # Behavioral health case study
├── case-pricing.html       # Pricing analysis case study
├── css/
│   └── style.css          # Main stylesheet
└── assets/
    ├── SPD_Resume_2025.pdf
    ├── SPD_3S_Pricing_Analysis.pdf
    ├── Clearpath_FY1_Operating_Review.pdf
    ├── Clearpath_FY1_Operating_Review.pptx
    ├── clearpath_raw_data.xlsx
    └── Methodology_Behind_The_Scenes.pdf
```

## Step by Step GitHub Pages Deployment

### 1. Prepare Your Files

Make sure you have all files downloaded from the zip.

### 2. Go to Your GitHub Repo

Navigate to: https://github.com/spdilly/Dillard---Portfolio

### 3. Upload Files

**Method A: GitHub Web Interface**
1. Click "Add file" → "Upload files"
2. Drag and drop all files and folders
3. Commit with message like "Portfolio site v1"

**Method B: Git Command Line**
```bash
git clone https://github.com/spdilly/Dillard---Portfolio.git
cd Dillard---Portfolio
# Copy all portfolio files here
git add .
git commit -m "Portfolio site v1"
git push origin main
```

### 4. Enable GitHub Pages

1. Go to repo Settings
2. Scroll to "Pages" in left sidebar
3. Under "Source", select "Deploy from a branch"
4. Select "main" branch and "/ (root)" folder
5. Click Save

### 5. Access Your Site

After a few minutes, your site will be live at:
`https://spdilly.github.io/Dillard---Portfolio/`

## Customization

### Change Colors
Edit `css/style.css` and modify the CSS variables at the top:
```css
:root {
  --navy: #1C3A5F;
  --green: #00A651;
  /* etc */
}
```

### Add a Photo
Replace the placeholder in `about.html`. Find the `.about-photo` div and add:
```html
<img src="assets/your-photo.jpg" class="about-photo" alt="Sean Dillard">
```

### Add More Case Studies
1. Duplicate `case-clearpath.html`
2. Update content
3. Add a new card to `index.html`

### Stock Photos Used
The case study cards use Unsplash images:
- Healthcare: https://unsplash.com/photos/person-holding-white-pill-bottle-zsogEQOMpbM
- Roofing: https://unsplash.com/photos/aerial-view-of-city-buildings-during-daytime-T5pL6ciEn-I

These are hotlinked. To self-host, download and place in `images/` folder.

## Technical Notes

- Pure HTML/CSS, no JavaScript required
- Google Fonts (Inter) loaded from CDN
- PDFs embedded using `<iframe>` 
- Mobile responsive
- Minimal dependencies

## License

Personal portfolio. All case study content © Sean Dillard.
