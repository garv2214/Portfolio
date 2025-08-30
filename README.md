# Personal Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript. Features a clean design, smooth animations, and mobile-first responsive layout.

## 🚀 Features

- **Responsive Design**: Works perfectly on all devices
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Mobile Navigation**: Hamburger menu for mobile devices
- **Smooth Scrolling**: Seamless navigation between sections
- **Contact Form**: Functional contact form with validation
- **Interactive Elements**: Hover effects and animations
- **SEO Optimized**: Semantic HTML structure
- **Fast Loading**: Optimized CSS and JavaScript

## 📁 File Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## 🛠️ Setup Instructions

1. **Clone or Download**: Get the portfolio files to your local machine
2. **Open in Browser**: Simply open `index.html` in your web browser
3. **Local Development**: Use a local server for development (recommended)

### Using a Local Server (Recommended)

```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (if you have http-server installed)
npx http-server

# Using PHP
php -S localhost:8000
```

Then open `http://localhost:8000` in your browser.

## ✏️ Customization Guide

### 1. Personal Information

Edit `index.html` to update your personal details:

```html
<!-- Update your name -->
<h1 class="hero-title">
    Hi, I'm <span class="highlight">Your Name</span>
</h1>

<!-- Update your title -->
<p class="hero-subtitle">Full Stack Developer & Designer</p>

<!-- Update your description -->
<p class="hero-description">
    I create beautiful, functional, and user-centered digital experiences.
    Passionate about clean code and innovative solutions.
</p>
```

### 2. About Section

Update the about section with your personal story:

```html
<div class="about-text">
    <p>
        I'm a passionate developer with a love for creating innovative digital solutions. 
        With expertise in modern web technologies, I focus on building scalable applications 
        that provide exceptional user experiences.
    </p>
    <!-- Add more paragraphs about yourself -->
</div>
```

### 3. Skills & Technologies

Modify the skills section to match your expertise:

```html
<div class="skill-category">
    <h3>Frontend</h3>
    <div class="skill-items">
        <div class="skill-item">
            <i class="fab fa-html5"></i>
            <span>HTML5</span>
        </div>
        <!-- Add/remove skills as needed -->
    </div>
</div>
```

### 4. Projects

Update the projects section with your actual work:

```html
<div class="project-card">
    <div class="project-image">
        <i class="fas fa-project-diagram"></i>
    </div>
    <div class="project-content">
        <h3>Your Project Name</h3>
        <p>Description of your project and what it does.</p>
        <div class="project-tech">
            <span>Technology 1</span>
            <span>Technology 2</span>
        </div>
        <div class="project-links">
            <a href="your-demo-link" class="btn btn-small">Live Demo</a>
            <a href="your-github-link" class="btn btn-small btn-outline">GitHub</a>
        </div>
    </div>
</div>
```

### 5. Contact Information

Update your contact details:

```html
<div class="contact-methods">
    <div class="contact-method">
        <i class="fas fa-envelope"></i>
        <span>your.actual.email@example.com</span>
    </div>
    <div class="contact-method">
        <i class="fas fa-phone"></i>
        <span>+1 (555) 123-4567</span>
    </div>
    <div class="contact-method">
        <i class="fas fa-map-marker-alt"></i>
        <span>Your City, Country</span>
    </div>
</div>
```

### 6. Social Media Links

Update your social media profiles:

```html
<div class="social-links">
    <a href="your-github-url" class="social-link"><i class="fab fa-github"></i></a>
    <a href="your-linkedin-url" class="social-link"><i class="fab fa-linkedin"></i></a>
    <a href="your-twitter-url" class="social-link"><i class="fab fa-twitter"></i></a>
    <a href="your-instagram-url" class="social-link"><i class="fab fa-instagram"></i></a>
</div>
```

### 7. Styling Customization

Modify `styles.css` to change colors, fonts, and layout:

```css
/* Change primary color */
:root {
    --primary-color: #2563eb;
    --secondary-color: #fbbf24;
    --text-color: #333;
    --background-color: #f8fafc;
}

/* Update hero background */
.hero {
    background: linear-gradient(135deg, #your-color-1 0%, #your-color-2 100%);
}
```

## 🌐 Deployment Options

### 1. GitHub Pages (Free)

1. Create a new GitHub repository
2. Upload your portfolio files
3. Go to Settings > Pages
4. Select source branch (usually `main`)
5. Your portfolio will be available at `https://username.github.io/repository-name`

### 2. Netlify (Free)

1. Drag and drop your portfolio folder to [Netlify](https://netlify.com)
2. Get a free subdomain
3. Optionally connect your custom domain

### 3. Vercel (Free)

1. Install Vercel CLI: `npm i -g vercel`
2. Run `vercel` in your portfolio directory
3. Follow the prompts to deploy

### 4. Traditional Web Hosting

Upload files via FTP to any web hosting service.

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🔧 Advanced Customization

### Adding New Sections

1. Add HTML structure in `index.html`
2. Add corresponding CSS in `styles.css`
3. Add navigation link in the navbar
4. Update JavaScript if needed

### Custom Animations

Modify the CSS animations in `styles.css`:

```css
@keyframes yourAnimation {
    from {
        /* starting state */
    }
    to {
        /* ending state */
    }
}
```

### Form Backend Integration

Replace the form handling in `script.js` with your preferred backend:

```javascript
// Example with fetch API
fetch('/api/contact', {
    method: 'POST',
    headers: {
        'Content-Type': 'application/json',
    },
    body: JSON.stringify(formData)
})
.then(response => response.json())
.then(data => {
    showNotification('Message sent successfully!', 'success');
});
```

## 📞 Support

If you need help customizing your portfolio:

1. Check the HTML structure and CSS classes
2. Use browser developer tools to inspect elements
3. Modify one section at a time
4. Test changes on different screen sizes

## 📄 License

This portfolio template is free to use and modify for personal and commercial projects.

## 🙏 Acknowledgments

- Font Awesome for icons
- Google Fonts for typography
- Modern CSS techniques and best practices

---

**Happy coding! 🚀**

Your portfolio is now ready to showcase your skills and projects to the world!
