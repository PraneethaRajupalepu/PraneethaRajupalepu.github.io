# Praneetha's Portfolio Website

A modern, advanced portfolio website built with HTML, CSS, and JavaScript. This is a fully responsive, feature-rich portfolio that showcases projects, skills, experience, and contact information.

## Features

### 🎨 Modern Design
- **Dark Theme**: Elegant dark background with vibrant gradient accents
- **Glassmorphism**: Modern blur effects and transparent overlays
- **Responsive Layout**: Mobile-first design that works on all devices
- **Smooth Animations**: Subtle transitions and scroll animations

### 📱 Responsive Design
- Desktop, tablet, and mobile optimized
- Hamburger menu for mobile navigation
- Flexible grid layouts

### ✨ Interactive Elements
- **Smooth Navigation**: Scroll to sections with smooth animation
- **Form Validation**: Contact form with feedback
- **Typing Animation**: Hero subtitle with typewriter effect
- **Counter Animation**: Animated statistics
- **Scroll Animations**: Elements fade in as you scroll
- **Custom Cursor**: Interactive cursor effect
- **Hover Effects**: Interactive feedback on buttons and cards

### 📄 Sections Included

1. **Navigation Bar**
   - Sticky navigation with smooth scrolling
   - Mobile-responsive hamburger menu
   - Active link highlighting

2. **Hero Section**
   - Compelling introduction
   - Call-to-action buttons
   - Social media links
   - Animated background elements

3. **About Section**
   - Professional summary
   - Key statistics with counters
   - Personal insights

4. **Skills Section**
   - Categorized skills (Frontend, Backend, DevOps, Databases)
   - Hover effects and animations
   - Technology tags

5. **Experience Section**
   - Timeline layout
   - Job positions and descriptions
   - Key responsibilities

6. **Projects Section**
   - Featured project cards
   - Project descriptions
   - Technology stack for each project
   - Links to live demo and source code

7. **Contact Section**
   - Contact information
   - Contact form
   - Email and phone links

8. **Footer**
   - Social media links
   - Copyright information

## File Structure

```
Portfolio_website_Gitio/
├── index.html      # Main HTML file
├── styles.css      # CSS styling and animations
├── script.js       # JavaScript interactivity
└── README.md       # This file
```

## Getting Started

### Option 1: Using a Local Server (Recommended)
1. Open the project folder in your preferred code editor
2. Install a live server extension (e.g., "Live Server" for VS Code)
3. Right-click on `index.html` and select "Open with Live Server"
4. The website will open in your browser at `http://localhost:5500`

### Option 2: Direct File Opening
1. Navigate to the project folder
2. Double-click `index.html` to open it in your default browser

### Option 3: Python HTTP Server
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```
Then open `http://localhost:8000` in your browser.

## Customization

### Update Personal Information
Edit `index.html` and replace:
- Hero section text
- About section content
- Skills and technologies
- Experience details
- Project information
- Contact details

### Change Colors
Edit `styles.css` and modify the CSS custom properties in `:root`:
```css
:root {
    --primary-color: #6366f1;      /* Main accent color */
    --secondary-color: #8b5cf6;    /* Secondary accent */
    --accent-color: #ec4899;       /* Accent highlights */
    --dark-bg: #0f172a;            /* Background */
    --text-primary: #f1f5f9;       /* Main text */
    /* ... other colors ... */
}
```

### Add More Projects
Duplicate a project card in the projects section and update the content:
```html
<div class="project-card">
    <div class="project-header">
        <h3>Your Project Name</h3>
        <div class="project-links">
            <a href="#" class="project-link">Live</a>
            <a href="#" class="project-link">Code</a>
        </div>
    </div>
    <p class="project-description">Your project description</p>
    <div class="project-tech">
        <span>Technology 1</span>
        <span>Technology 2</span>
    </div>
</div>
```

## Advanced Features Explained

### Animations
- **Floating Background**: Subtle floating animation in the hero section
- **Typing Effect**: Hero subtitle appears with typewriter effect
- **Scroll Animations**: Cards fade in as they come into view
- **Counter Animation**: Statistics count up when section is visible
- **Gradient Text**: Smooth color transitions on headings

### JavaScript Interactivity
- **Mobile Menu**: Toggle navigation menu on small screens
- **Smooth Scrolling**: Navigate between sections smoothly
- **Active Link Tracking**: Highlight current section in navigation
- **Form Handling**: Process contact form submissions
- **Intersection Observer**: Efficient scroll-based animations
- **Custom Cursor**: Interactive cursor that responds to elements

### CSS Features
- **CSS Grid**: Responsive layouts for projects and skills
- **Flexbox**: Flexible component layouts
- **Gradients**: Beautiful linear and radial gradients
- **Backdrop Filter**: Glassmorphic effects
- **CSS Variables**: Easy customization of colors and values
- **Media Queries**: Responsive breakpoints for all devices

## Keyboard Shortcuts
- **H**: Jump to home section
- **C**: Jump to contact section

## Browser Support
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Performance Considerations
- Optimized CSS with minimal repaints
- Efficient JavaScript event listeners
- Lazy loading capabilities
- Mobile-first responsive design
- Minimal dependencies (pure HTML, CSS, JS)

## Deployment

### GitHub Pages
1. Create a GitHub repository named `username.github.io`
2. Push the files to the repository
3. Access your portfolio at `https://username.github.io`

### Netlify
1. Connect your GitHub repository
2. Set build settings (no build needed)
3. Deploy automatically

### Vercel
1. Import your project from GitHub
2. Deploy with one click
3. Custom domain support

## Tips for Success

1. **Update Content**: Replace all placeholder text with your actual information
2. **Add Real Projects**: Include links to your actual projects and GitHub
3. **Professional Photos**: Add a profile picture if desired
4. **Social Links**: Update social media URLs
5. **Contact Form**: Implement backend service (e.g., Formspree, Netlify Forms)
6. **SEO**: Update meta tags in the head section
7. **Testing**: Test on multiple devices and browsers

## Future Enhancements

- Dark/Light theme toggle
- Blog section
- Testimonials/recommendations
- More detailed project pages
- Resume download button
- Multi-language support
- Backend form submission
- Analytics integration

## License

This portfolio template is free to use and modify. Feel free to adapt it for your personal use.

## Support

For issues or suggestions, please check the code comments and customize as needed.

---

**Created**: January 2026  
**Version**: 1.0  
**Status**: Ready to Deploy
