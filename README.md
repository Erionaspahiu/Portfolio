# Modern Portfolio Website

A beautiful, responsive portfolio website inspired by the Gerold theme design. Perfect for designers, developers, and creative professionals to showcase their work.

## Features

- 🎨 Modern, clean design with gradient accents
- 📱 Fully responsive for all devices
- ⚡ Smooth animations and transitions
- 🎯 Portfolio filtering system
- 📧 Contact form with validation
- 🔍 SEO optimized structure
- 🚀 Fast loading and performance

## Getting Started

### 1. Setup
1. Download or clone this repository
2. Open `index.html` in your web browser
3. Start customizing the content

### 2. Customization

#### Personal Information
Edit the following in `index.html`:

```html
<!-- Replace "Your Name" with your actual name -->
<h2>Your Name</h2>

<!-- Update the hero section -->
<h1 class="hero-title">Hi, I'm <span class="highlight">Your Name</span></h1>
<h2 class="hero-subtitle">UI/UX Designer & Developer</h2>

<!-- Update contact information -->
<p>your.email@example.com</p>
<p>+1 (555) 123-4567</p>
<p>Your City, Country</p>
```

#### Profile Image
Replace the placeholder image in the hero section:
```html
<img src="path/to/your/photo.jpg" alt="Your Name">
```

#### Portfolio Projects
Add your Figma projects by updating the portfolio section:

```html
<div class="portfolio-item" data-category="ui-ux">
    <div class="portfolio-image">
        <img src="path/to/your/project-image.jpg" alt="Project Name">
        <div class="portfolio-overlay">
            <div class="portfolio-info">
                <h3>Your Project Name</h3>
                <p>Project Description</p>
                <a href="your-figma-link" class="portfolio-link" target="_blank">
                    <i class="fas fa-external-link-alt"></i>
                </a>
            </div>
        </div>
    </div>
</div>
```

#### Skills
Update the skills section with your expertise:
```html
<div class="skill-tags">
    <span class="skill-tag">Figma</span>
    <span class="skill-tag">Adobe XD</span>
    <span class="skill-tag">Sketch</span>
    <span class="skill-tag">HTML/CSS</span>
    <span class="skill-tag">JavaScript</span>
    <span class="skill-tag">UI/UX Design</span>
</div>
```

#### Services
Customize the services you offer:
```html
<div class="service-card">
    <div class="service-icon">
        <i class="fas fa-palette"></i>
    </div>
    <h3>Your Service</h3>
    <p>Service description</p>
</div>
```

### 3. Adding Your Figma Projects

1. **Screenshot Method:**
   - Take screenshots of your Figma designs
   - Save them in a `images` folder
   - Update the portfolio items with your images

2. **Direct Figma Links:**
   - Use Figma's share links
   - Update the portfolio link to point to your Figma project

3. **Embed Method:**
   - Use Figma's embed feature
   - Replace the image with an iframe

### 4. Color Customization

The main colors can be customized in `styles.css`:

```css
/* Primary gradient colors */
background: linear-gradient(135deg, #6366f1, #8b5cf6);

/* You can change these hex values to match your brand */
```

### 5. Fonts

The website uses Inter font from Google Fonts. You can change it by:
1. Updating the Google Fonts link in the HTML
2. Changing the font-family in CSS

## File Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js           # JavaScript functionality
├── README.md           # This file
└── images/             # Your project images (create this folder)
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Performance Tips

1. Optimize your images before uploading
2. Use WebP format for better compression
3. Compress CSS and JavaScript for production
4. Host images on a CDN for faster loading

## Deployment

### GitHub Pages
1. Push your code to a GitHub repository
2. Go to Settings > Pages
3. Select your branch and save

### Netlify
1. Drag and drop your folder to Netlify
2. Your site will be live instantly

### Vercel
1. Connect your GitHub repository
2. Deploy automatically on push

## Customization Examples

### Dark Theme
Add this CSS to create a dark theme:
```css
body {
    background: #1a1a1a;
    color: #ffffff;
}

.navbar {
    background: rgba(26, 26, 26, 0.95);
}
```

### Different Color Schemes
- **Blue Theme:** `#3b82f6` to `#1d4ed8`
- **Green Theme:** `#10b981` to `#059669`
- **Purple Theme:** `#8b5cf6` to `#7c3aed`

## Support

If you need help customizing your portfolio:
1. Check the HTML comments for guidance
2. Review the CSS classes for styling options
3. Test changes in a local environment first

## License

This project is open source and available under the [MIT License](LICENSE).

---

**Happy coding! 🚀** 