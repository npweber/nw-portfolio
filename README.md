# Software Developer Portfolio Website

A modern, responsive, single-page portfolio website built with HTML, CSS, and JavaScript. Perfect for showcasing your software development skills and projects.

## Features

- **Modern Design**: Clean, professional design with smooth animations
- **Fully Responsive**: Works perfectly on desktop, tablet, and mobile devices
- **Interactive Elements**: Smooth scrolling, hover effects, and form validation
- **Mobile Navigation**: Hamburger menu for mobile devices
- **Contact Form**: Functional contact form with validation
- **Loading Animation**: Professional loading screen
- **SEO Optimized**: Semantic HTML structure

## File Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## Customization Guide

### 1. Personal Information

Update the following in `index.html`:

- **Name**: Replace "Your Name" in the hero section
- **Title**: Change "Software Developer" to your preferred title
- **Description**: Update the hero description to match your background
- **Contact Information**: Update email, phone, and location in the contact section
- **Social Links**: Add your actual social media URLs in the footer

### 2. About Section

- **Experience**: Update the years of experience
- **Projects**: Change the number of completed projects
- **Technologies**: Update the number of technologies you work with
- **Bio**: Customize the about text to reflect your background and goals

### 3. Skills Section

Add or remove skills by editing the skills section in `index.html`:

```html
<div class="skill-item">
    <i class="fab fa-[technology-icon]"></i>
    <span>[Technology Name]</span>
</div>
```

Common FontAwesome icons for technologies:
- `fa-html5` - HTML5
- `fa-css3-alt` - CSS3
- `fa-js` - JavaScript
- `fa-react` - React
- `fa-node-js` - Node.js
- `fa-python` - Python
- `fa-database` - SQL/Database
- `fa-git-alt` - Git

### 4. Projects Section

Replace the sample projects with your own:

```html
<div class="project-card">
    <div class="project-image">
        <div class="project-placeholder">
            <i class="fas fa-[project-icon]"></i>
        </div>
    </div>
    <div class="project-content">
        <h3>[Project Name]</h3>
        <p>[Project Description]</p>
        <div class="project-tech">
            <span>[Technology 1]</span>
            <span>[Technology 2]</span>
            <span>[Technology 3]</span>
        </div>
        <div class="project-links">
            <a href="[GitHub URL]" class="project-link"><i class="fab fa-github"></i> Code</a>
            <a href="[Live URL]" class="project-link"><i class="fas fa-external-link-alt"></i> Live</a>
        </div>
    </div>
</div>
```

### 5. Color Scheme

To change the color scheme, update the CSS variables in `styles.css`:

```css
:root {
    --primary-color: #2563eb;
    --secondary-color: #fbbf24;
    --gradient-start: #667eea;
    --gradient-end: #764ba2;
    --text-color: #333;
    --background-color: #ffffff;
}
```

### 6. Adding Real Images

Replace the placeholder icons with real images:

1. Add your profile picture:
```html
<div class="hero-image">
    <img src="path/to/your-photo.jpg" alt="Your Name" class="profile-image">
</div>
```

2. Add project screenshots:
```html
<div class="project-image">
    <img src="path/to/project-screenshot.jpg" alt="Project Name">
</div>
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Performance Features

- **Lazy Loading**: Images load only when needed
- **Smooth Animations**: Optimized CSS transitions
- **Minimal JavaScript**: Lightweight and fast
- **Responsive Images**: Automatically scaled for different screen sizes

## Deployment

### GitHub Pages
1. Push your code to a GitHub repository
2. Go to Settings > Pages
3. Select your branch and save

### Netlify
1. Drag and drop your folder to Netlify
2. Your site will be live instantly

### Vercel
1. Connect your GitHub repository to Vercel
2. Deploy automatically on every push

## Customization Tips

1. **Keep it Simple**: Don't overcrowd with too many elements
2. **Use High-Quality Images**: Ensure images are optimized for web
3. **Test on Mobile**: Always test the responsive design
4. **Update Regularly**: Keep your projects and skills current
5. **Add Analytics**: Consider adding Google Analytics for insights

## Troubleshooting

### Form Not Working
The contact form is set up for demonstration. To make it functional:
1. Use a form service like Formspree or Netlify Forms
2. Or implement your own backend API

### Images Not Loading
- Check file paths are correct
- Ensure images are in the same directory or update paths
- Verify image file names match exactly

### Mobile Menu Not Working
- Ensure JavaScript is enabled
- Check for console errors
- Verify all CSS classes are properly defined

## License

This project is open source and available under the [MIT License](LICENSE).

## Support

If you need help customizing your portfolio, feel free to:
- Check the code comments for guidance
- Review the HTML structure for reference
- Test changes in a local environment first

---

**Happy coding! 🚀** 