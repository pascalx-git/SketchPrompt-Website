# SketchPrompt Website

This is the marketing website for SketchPrompt, a powerful Cursor IDE extension for visual thinking and AI collaboration.

## 🚀 Quick Start

1. **Local Development**
   ```bash
   # Navigate to the website directory
   cd website
   
   # Open index.html in your browser
   open index.html
   # Or use a local server
   python -m http.server 8000
   # Then visit http://localhost:8000
   ```

2. **Deploy to GitHub Pages**
   ```bash
   # Create a new repository for the website
   git init
   git add .
   git commit -m "Initial website commit"
   git branch -M main
   git remote add origin https://github.com/yourusername/sketchprompt-website.git
   git push -u origin main
   
   # Enable GitHub Pages in repository settings
   # Go to Settings > Pages > Source > Deploy from a branch
   # Select main branch and / (root) folder
   ```

3. **Custom Domain Setup**
   - Purchase `sketch-prompt.com` from your domain registrar
   - In your domain registrar's DNS settings, add these records:
     ```
     Type: A
     Name: @
     Value: 185.199.108.153
     Value: 185.199.109.153
     Value: 185.199.110.153
     Value: 185.199.111.153
     ```
   - In GitHub repository settings, go to Pages and add your custom domain
   - Check "Enforce HTTPS" option

## 📁 File Structure

```
website/
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js           # JavaScript functionality
├── images/             # Image assets
│   ├── logo.png        # SketchPrompt logo
│   ├── favicon.png     # Favicon
│   ├── hero-screenshot.png  # Hero section screenshot
│   ├── usage-demo.png  # Usage demonstration image
│   └── og-image.png    # Open Graph image for social sharing
└── README.md           # This file
```

## 🎨 Customization

### Colors
The website uses CSS custom properties for easy color customization. Edit the `:root` section in `styles.css`:

```css
:root {
    --primary-color: #6366f1;
    --secondary-color: #8b5cf6;
    --accent-color: #06b6d4;
    /* ... other colors */
}
```

### Content
- Update the hero section in `index.html`
- Modify feature descriptions
- Update installation steps
- Edit roadmap content

### Images
Replace the placeholder images in the `images/` directory:
- `hero-screenshot.png` - Screenshot of SketchPrompt in action
- `usage-demo.png` - Demo showing how to use the extension
- `og-image.png` - Social media sharing image (1200x630px)

## 🔧 Features

- **Responsive Design** - Works on all devices
- **Modern UI** - Clean, professional design
- **Smooth Animations** - CSS transitions and JavaScript animations
- **Mobile Navigation** - Hamburger menu for mobile devices
- **Copy Code** - Click to copy installation commands
- **SEO Optimized** - Meta tags and Open Graph support
- **Accessibility** - Keyboard navigation and screen reader support

## 📱 Mobile Support

The website is fully responsive and includes:
- Mobile-first design approach
- Touch-friendly navigation
- Optimized images and layouts
- Fast loading times

## 🚀 Performance

- Optimized images and assets
- Minified CSS and JavaScript (for production)
- Fast loading times
- SEO best practices

## 🔗 Links

- **GitHub Repository**: https://github.com/pascalx-git/SketchPrompt
- **Cursor IDE**: https://cursor.sh
- **TLDraw**: https://tldraw.dev

## 📄 License

MIT License - same as the main SketchPrompt project.

## 🤝 Contributing

1. Fork the repository
2. Make your changes
3. Test locally
4. Submit a pull request

---

**Note**: Replace placeholder images with actual screenshots and demo images before deploying to production. 