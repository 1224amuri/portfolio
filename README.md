# Jagrut Amuri - Portfolio Website

A nature-inspired portfolio website showcasing work at the intersection of biology, technology, and storytelling.

## 🌿 Features

- **Organic Design**: Nature-inspired color palette with earthy tones
- **Smooth Animations**: Intersection observers and scroll-triggered effects
- **Responsive**: Fully responsive design that works on all devices
- **Accessible**: Semantic HTML and ARIA labels where needed
- **Performance**: Optimized for fast loading and smooth interactions

## 🚀 Deploying to GitHub Pages

### Method 1: Using GitHub Web Interface

1. Create a new repository on GitHub (e.g., `portfolio`)
2. Upload these files to your repository:
   - `index.html`
   - `styles.css`
   - `script.js`
   - `README.md` (this file)

3. Go to repository Settings → Pages
4. Under "Source", select the branch (usually `main` or `master`)
5. Click Save
6. Your site will be published at: `https://[your-username].github.io/[repository-name]`

### Method 2: Using Git Command Line

```bash
# Initialize git repository
git init

# Add all files
git add .

# Commit files
git commit -m "Initial commit: Portfolio website"

# Add remote repository (replace with your repo URL)
git remote add origin https://github.com/[your-username]/[repository-name].git

# Push to GitHub
git branch -M main
git push -u origin main
```

Then enable GitHub Pages in your repository settings.

### Method 3: For username.github.io

If you want your portfolio at `https://[your-username].github.io`:

1. Create a repository named exactly: `[your-username].github.io`
2. Upload your files
3. Your site will automatically be published at that URL

## 📁 File Structure

```
portfolio/
├── index.html       # Main HTML file
├── styles.css       # All styling
├── script.js        # Interactive functionality
└── README.md        # This file
```

## 🎨 Customization

### Colors
Edit the CSS variables in `styles.css`:

```css
:root {
    --color-forest: #1a3a2e;
    --color-moss: #4a7c59;
    --color-sage: #8b9d83;
    /* ... more colors */
}
```

### Fonts
The site uses Google Fonts:
- **Display**: Playfair Display
- **Body**: Crimson Pro
- **Sans**: DM Sans

To change fonts, update the Google Fonts link in `index.html` and the CSS variables in `styles.css`.

### Content
All content can be edited directly in `index.html`. The structure is organized by sections:
- Hero
- About
- Guiding Principles
- Practice I: Workshops
- Practice II: Mediation
- Practice III: Ecology & Field Work
- What's Next
- Footer

## 🔧 Technical Details

- **No build process required** - works with plain HTML, CSS, and JavaScript
- **No dependencies** - only uses Google Fonts CDN
- **Browser support**: All modern browsers (Chrome, Firefox, Safari, Edge)
- **Mobile-first responsive design**

## 📱 Mobile Support

The website is fully responsive with breakpoints at:
- Desktop: > 768px
- Tablet: 481px - 768px
- Mobile: ≤ 480px

## ⚡ Performance

- Optimized animations using CSS transforms
- Debounced scroll events
- Intersection Observer for lazy animations
- Minimal external dependencies
- Font preloading for better rendering

## 🐛 Browser Compatibility

Tested and working on:
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📄 License

This portfolio website is created for Jagrut Amuri. Feel free to use the code structure for your own portfolio, but please replace the content with your own.

## 🌟 Credits

Design and development inspired by the intersection of nature and technology, reflecting the ethos of the portfolio content.

---

**Note**: Remember to replace placeholder content and customize the colors, fonts, and layout to match your personal brand!
