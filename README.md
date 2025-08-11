# Mohamed Khaldi - Portfolio Website

🚀 A modern, responsive portfolio website showcasing my skills, projects, and experience as a Full Stack Developer.

## 🌟 Features

- **Responsive Design**: Fully responsive layout that works seamlessly on all devices
- **Interactive UI**: Smooth animations and transitions for enhanced user experience
- **Project Showcase**: Dynamic project filtering system to showcase different categories of work
- **Skills Section**: Animated skill bars showing proficiency levels
- **Contact Form**: Validated contact form with real-time feedback
- **Performance Optimized**: Fast loading times with optimized assets
- **Accessibility**: Built with accessibility best practices in mind

## 🛠️ Technologies Used

### Frontend
- HTML5
- CSS3 (with custom animations)
- JavaScript (ES6+)
- Font Awesome Icons
- Google Fonts (Poppins)

### Features Implementation
- Intersection Observer API for scroll animations
- CSS Grid and Flexbox for layouts
- Form validation with JavaScript
- Smooth scrolling navigation
- Mobile-first responsive design

## 📁 Project Structure

```
portfolio/
├── index.html          # Main HTML file
├── css/
│   └── styles.css      # All styling and animations
├── js/
│   └── script.js       # JavaScript functionality
├── images/             # Image assets (add your images here)
├── CNAME              # Custom domain configuration
└── README.md          # Project documentation
```

## 🚀 Getting Started

### Prerequisites
- A modern web browser
- A text editor (VS Code recommended)
- Git (for version control)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/khaldi-med/khaldi-med.github.io.git
```

2. Navigate to the project directory:
```bash
cd khaldi-med.github.io
```

3. Open `index.html` in your browser or use a local server:
```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve
```

## 📝 Customization

### Personal Information
1. Update the name and title in `index.html`
2. Replace placeholder email and phone in the contact section
3. Update social media links with your profiles

### Adding Your Photo
1. Add your profile photo to the `images/` directory
2. Update the image source in the hero section:
```html
<img src="images/your-photo.jpg" alt="Your Name">
```

### Projects
1. Replace placeholder project images in `images/` directory
2. Update project details in the projects section
3. Add actual project links (GitHub and live demos)

### Skills
Modify skill levels in `index.html` by changing the `data-level` attribute:
```html
<div class="skill-level" data-level="85"></div>
```

## 🎨 Color Customization

The main color scheme uses CSS variables. To change colors, modify these in `styles.css`:
- Primary color: `#4f46e5`
- Secondary color: `#764ba2`
- Accent color: `#ff6b6b`

## 📱 Responsive Breakpoints

- Desktop: 1200px and above
- Tablet: 768px - 1199px
- Mobile: Below 768px

## 🔧 Features in Detail

### Loading Animation
Smooth loading screen that fades out when the page is ready

### Navigation
- Sticky navigation bar with scroll effect
- Mobile hamburger menu
- Active section highlighting
- Smooth scroll to sections

### Animations
- Scroll-triggered animations using Intersection Observer
- Counter animation for statistics
- Skill bar animations
- Typing effect for hero subtitle
- Parallax scrolling effect

### Project Filter
Filter projects by category:
- All
- Web Development
- Mobile
- Design

### Contact Form
- Real-time validation
- Error messages
- Success feedback
- Email validation

## 🚀 Deployment

This site is configured for GitHub Pages deployment:

1. Push your changes to GitHub:
```bash
git add .
git commit -m "Update portfolio"
git push origin main
```

2. Enable GitHub Pages in repository settings
3. Your site will be available at: `https://khaldi-med.github.io`

## 📈 Performance Optimization Tips

1. **Images**: 
   - Use optimized image formats (WebP, compressed JPEG)
   - Implement lazy loading for images
   - Use appropriate image sizes

2. **Code**:
   - Minify CSS and JavaScript for production
   - Enable browser caching
   - Use CDN for external libraries

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👤 Author

**Mohamed Khaldi**

- GitHub: [@khaldi-med](https://github.com/khaldi-med)
- Email: contact@medkhaldi.me
- Website: [medkhaldi.me](https://medkhaldi.me)

## 🙏 Acknowledgments

- Font Awesome for icons
- Google Fonts for typography
- Inspiration from various portfolio designs

---

⭐ Star this repo if you find it helpful!
