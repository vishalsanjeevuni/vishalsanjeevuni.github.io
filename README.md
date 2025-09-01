# Portfolio Website

A simple, clean GitHub Pages website inspired by the beautiful [astro-theme-cactus](https://github.com/chrismwilliams/astro-theme-cactus) design.

## ✨ Features

- **Clean Design**: Minimalist aesthetic inspired by astro-theme-cactus
- **Dark/Light Theme**: Toggle between themes with persistent storage
- **Responsive**: Mobile-first design that works on all devices
- **Accessible**: Semantic HTML, keyboard navigation, and screen reader support
- **Fast**: Vanilla JavaScript with no dependencies
- **GitHub Pages Ready**: Static files ready for deployment

## 🚀 Quick Start

1. **Fork this repository** or download the files
2. **Customize the content** in `index.html`
3. **Update your information**:
   - Replace contact links with your own
   - Add your projects and experience
   - Update the site title and description
4. **Deploy to GitHub Pages**:
   - Go to repository Settings
   - Navigate to Pages section
   - Select source branch (usually `main`)
   - Your site will be available at `https://yourusername.github.io/repository-name`

## 📁 File Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # All styling and theme variables
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## 🎨 Customization

### Colors and Theming

The site uses CSS custom properties for easy theming. You can modify colors in `styles.css`:

```css
:root {
    --color-global-bg: oklch(98.48% 0 0);
    --color-global-text: oklch(26.99% 0.0096 235.05);
    --color-accent: oklch(55.27% 0.195 19.06);
    /* ... more colors */
}
```

### Content Sections

The site is organized into main sections:
- **Home**: Welcome message and introduction
- **About**: Skills, experience, and background
- **Projects**: Featured work with links
- **Contact**: Social links and contact information

### Adding Projects

To add a new project, copy this structure in the Projects section:

```html
<div class="project-card">
    <h3>Project Name</h3>
    <p>Project description goes here...</p>
    <div class="project-links">
        <a href="#" class="cactus-link">View Demo</a>
        <a href="#" class="cactus-link">Source Code</a>
    </div>
</div>
```

## 🛠️ Technical Details

### Built With
- **HTML5**: Semantic markup
- **CSS3**: Modern features like CSS Grid, Flexbox, and Custom Properties
- **Vanilla JavaScript**: No frameworks or dependencies
- **Web Standards**: Progressive enhancement and accessibility

### Browser Support
- Chrome/Edge 88+
- Firefox 78+
- Safari 14+
- Mobile browsers with modern CSS support

### Performance Features
- **Minimal JavaScript**: Only loads what's needed
- **CSS Custom Properties**: Efficient theming
- **Intersection Observer**: Smooth navigation highlighting
- **Reduced Motion Support**: Respects user preferences
- **Local Storage**: Theme preference persistence

## 🎯 Keyboard Shortcuts

- `Ctrl/Cmd + T`: Toggle theme
- `Escape`: Close mobile menu
- `Tab`: Navigate through focusable elements

## 📱 Mobile Features

- **Responsive Design**: Adapts to all screen sizes
- **Touch-Friendly**: Large tap targets and smooth interactions
- **Mobile Menu**: Collapsible navigation for small screens
- **Optimized Typography**: Readable on all devices

## 🌐 Deployment Options

### GitHub Pages (Recommended)
1. Push your code to a GitHub repository
2. Go to Settings > Pages
3. Select your source branch
4. Your site will be live at `https://username.github.io/repository-name`

### Other Static Hosts
This site works with any static hosting service:
- **Netlify**: Drag and drop deployment
- **Vercel**: Connect your GitHub repository
- **GitHub Codespaces**: Built-in preview
- **Local**: Open `index.html` in your browser

## 🎨 Design Inspiration

This site is inspired by the excellent [astro-theme-cactus](https://astro-cactus.chriswilliams.dev/) by Chris Williams. Key design elements borrowed:

- **Typography**: Monospace font (JetBrains Mono)
- **Color Palette**: Warm, accessible color scheme
- **Layout**: Clean, centered content with generous whitespace
- **Navigation**: Simple, effective menu design
- **Theme Toggle**: Elegant dark/light mode switching

## 🤝 Contributing

Feel free to:
- Report bugs or issues
- Suggest improvements
- Submit pull requests
- Share your customizations

## 📄 License

This project is open source and available under the MIT License.

## 🙏 Acknowledgments

- [astro-theme-cactus](https://github.com/chrismwilliams/astro-theme-cactus) - Design inspiration
- [JetBrains Mono](https://www.jetbrains.com/mono/) - Beautiful monospace font
- [GitHub Pages](https://pages.github.com/) - Free hosting platform

---

Built with ❤️ and inspired by the beautiful astro-theme-cactus design.
