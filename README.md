# Afnan's Portfolio Website

A modern, dark-themed portfolio website for Afnan, a 15-year-old freelance developer specializing in custom websites and Discord bots.

## 🚀 Features

### Design & UI
- **Dark Theme**: Sleek dark mode with electric blue accents
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **Modern Animations**: Smooth hover effects, scroll animations, and transitions
- **Clean Typography**: Inter font family for excellent readability
- **Card-based Layout**: Modern card design with soft shadows

### Sections
1. **Hero Section**: Bold headline with CTA buttons and animated code window
2. **Services**: Discord bots and website development services
3. **Portfolio**: Showcase of recent projects with tech stack tags
4. **Pricing**: Three-tier pricing structure for different service levels
5. **Testimonials**: Client reviews and feedback
6. **Contact**: Contact form and social media links
7. **Footer**: Social links and branding

### Interactive Features
- **Mobile Navigation**: Hamburger menu for mobile devices
- **Smooth Scrolling**: Seamless navigation between sections
- **Form Validation**: Contact form with email validation
- **Notification System**: Success/error messages for user feedback
- **Progress Bar**: Visual scroll progress indicator
- **Typing Animation**: Animated hero title text
- **Hover Effects**: Interactive elements with smooth transitions

## 🛠️ Technologies Used

- **HTML5**: Semantic markup structure
- **CSS3**: Modern styling with CSS Grid, Flexbox, and custom properties
- **JavaScript (ES6+)**: Interactive functionality and animations
- **Font Awesome**: Icons for services and social media
- **Google Fonts**: Inter font family

## 📁 Project Structure

```
Portolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript functionality
└── README.md           # Project documentation
```

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- No additional dependencies required

### Installation
1. Clone or download the project files
2. Open `index.html` in your web browser
3. The website will load with all features ready to use

### Local Development
For development purposes, you can use any local server:

```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (if you have http-server installed)
npx http-server

# Using PHP
php -S localhost:8000
```

Then visit `http://localhost:8000` in your browser.

## 🎨 Customization

### Colors
The color scheme is defined using CSS custom properties in `styles.css`:

```css
:root {
    --primary-color: #00d4ff;      /* Electric blue */
    --primary-dark: #0099cc;       /* Darker blue */
    --background-dark: #0a0a0a;    /* Main background */
    --background-card: #1a1a1a;    /* Card background */
    --text-primary: #ffffff;       /* Primary text */
    --text-secondary: #b0b0b0;     /* Secondary text */
}
```

### Content Updates
- **Personal Information**: Update the hero section text in `index.html`
- **Services**: Modify service descriptions and features
- **Portfolio**: Replace placeholder content with actual projects
- **Pricing**: Adjust pricing tiers and features
- **Contact**: Update Discord username and social media links

### Adding New Sections
1. Add HTML structure in `index.html`
2. Style the section in `styles.css`
3. Add any JavaScript functionality in `script.js`

## 📱 Responsive Breakpoints

- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: Below 768px
- **Small Mobile**: Below 480px

## 🔧 Browser Support

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## 🎯 Performance Features

- **Optimized Images**: Placeholder images with icons for fast loading
- **Throttled Scroll Events**: Performance-optimized scroll handling
- **CSS Animations**: Hardware-accelerated animations
- **Minimal Dependencies**: Only essential external resources

## 📞 Contact Integration

The contact form includes:
- Form validation
- Email format checking
- Success/error notifications
- Simulated form submission

To integrate with a real backend:
1. Replace the form submission handler in `script.js`
2. Add your backend endpoint URL
3. Handle form data according to your backend requirements

## 🌟 Key Features for Afnan

### Professional Presentation
- Clean, modern design that reflects technical expertise
- Age-appropriate yet professional tone
- Showcases both Discord bot and web development skills

### Client-Focused
- Clear service descriptions
- Transparent pricing structure
- Multiple contact options (Discord, WhatsApp)
- Client testimonials for social proof

### Technical Excellence
- Responsive design for all devices
- Fast loading and smooth animations
- Accessible navigation and interactions
- Modern web standards compliance

## 🚀 Deployment

### GitHub Pages
1. Push code to a GitHub repository
2. Enable GitHub Pages in repository settings
3. Select source branch (usually `main`)

### Netlify
1. Connect your GitHub repository to Netlify
2. Deploy automatically on code changes
3. Get a custom domain (optional)

### Vercel
1. Import your GitHub repository to Vercel
2. Automatic deployment and previews
3. Global CDN for fast loading

## 📝 License

This project is created for Afnan's personal use. Feel free to modify and customize for your own portfolio.

## 🤝 Contributing

This is a personal portfolio project, but suggestions and improvements are welcome!

---

**Made with ❤️ for Afnan - A talented young developer ready to build amazing projects!** 