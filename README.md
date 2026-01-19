# Crownstrike - Athletic Excellence

Premium athletic wear and sports equipment website featuring a bold crown and lightning bolt brand identity.

## 🚀 Features

- Responsive design for all devices
- Animated hero section with floating logo
- Mobile-friendly navigation menu
- Smooth scrolling navigation
- Modern gradient design with orange/gold brand colors
- Interactive hover effects
- Optimized for performance

## 📁 Project Structure

```
crownstrike-site/
├── index.html          # Main HTML file
├── css/
│   └── styles.css      # All styles
├── js/
│   └── main.js         # JavaScript functionality
└── README.md           # This file
```

## 🌐 Deployment Instructions

### Deploy to GitHub Pages

1. **Create a new GitHub repository**
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Crownstrike website"
   git branch -M main
   git remote add origin https://github.com/YOUR-USERNAME/crownstrike.git
   git push -u origin main
   ```

2. **Enable GitHub Pages**
   - Go to repository Settings
   - Navigate to Pages section
   - Source: Deploy from branch `main`
   - Folder: `/ (root)`
   - Click Save

3. **Your site will be live at:**
   `https://YOUR-USERNAME.github.io/crownstrike/`

### Deploy to Netlify

1. **Via Netlify CLI:**
   ```bash
   npm install -g netlify-cli
   netlify deploy --prod
   ```

2. **Via Netlify Dashboard:**
   - Drag and drop the entire `crownstrike-site` folder
   - Or connect your GitHub repository

### Deploy to Vercel

1. **Via Vercel CLI:**
   ```bash
   npm i -g vercel
   vercel --prod
   ```

2. **Via Vercel Dashboard:**
   - Import your GitHub repository
   - Deploy with default settings

## 🎨 Customization

### Colors
Main brand colors are defined in `css/styles.css`:
- Primary Orange: `#ff9900`
- Light Orange: `#ffb347`
- Dark Brown: `#1a0f00`, `#2d1a00`
- Lightning Blue: `#1e88e5`

### Content
- Update text in `index.html`
- Modify navigation links in the `<nav>` section
- Change feature cards in the `.features` section

### Logo
The crown and lightning bolt logo is an inline SVG in `index.html`. Modify the SVG paths to customize the design.

## 🔧 Technical Details

- Pure HTML, CSS, and JavaScript (no build process required)
- Google Fonts: Montserrat (700, 900 weights)
- Mobile-first responsive design
- CSS Grid for feature cards
- Flexbox for navigation and layout
- CSS animations for logo and hover effects

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📄 License

© 2026 Crownstrike. All Rights Reserved.

---

**Need help?** Open an issue on GitHub or contact support.
