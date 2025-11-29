# Luxe Interiors - Interior Design Website

A modern, responsive website for an interior design company featuring elegant design, smooth animations, and a comprehensive portfolio showcase.

![Luxe Interiors](https://images.pexels.com/photos/1648776/pexels-photo-1648776.jpeg?auto=compress&cs=tinysrgb&w=800)

## 🌟 Features

- **Fully Responsive Design** - Works seamlessly on desktop, tablet, and mobile devices
- **Modern UI/UX** - Clean, elegant interface with smooth animations and transitions
- **Multiple Pages** - Home, Services, Gallery/Portfolio, and Contact pages
- **Interactive Navigation** - Mobile-friendly hamburger menu with smooth scrolling
- **Service Showcase** - Comprehensive display of interior design services
- **Portfolio Gallery** - Organized showcase of projects by category (living rooms, kitchens, bedrooms, etc.)
- **Contact Form** - Functional contact form with validation
- **Professional Design** - Inspired by modern design trends and best practices

## 📁 Project Structure

```
interior-design-website/
├── index.html          # Home page with hero section and featured content
├── services.html       # Detailed services page with design process
├── gallery.html        # Portfolio gallery organized by room type
├── contact.html        # Contact form and business information
├── css/
│   └── styles.css      # Main stylesheet with responsive design
├── js/
│   └── script.js       # JavaScript for navigation, animations, and form handling
├── images/             # Folder for additional local images
└── README.md           # Project documentation
```

## 🎨 Design Features

### Color Palette
- Primary: `#2c3e50` (Dark Blue-Gray)
- Secondary: `#d4af37` (Gold)
- Accent: `#8b7355` (Brown)
- Background: `#f8f9fa` (Light Gray)

### Typography
- Font Family: Segoe UI, Tahoma, Geneva, Verdana, sans-serif
- Responsive font sizes using rem units
- Line height optimized for readability

### Key Components
- Fixed navigation header with scroll effects
- Hero sections with gradient overlays
- Service cards with hover effects
- Gallery grid with image overlays
- Contact form with validation
- Smooth scroll animations
- Mobile-responsive burger menu

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, or Edge)
- A local web server (optional but recommended)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/interior-design-website.git
   cd interior-design-website
   ```

2. **Open the website**
   
   **Option 1: Direct File Access**
   - Simply open `index.html` in your web browser

   **Option 2: Using Python HTTP Server**
   ```bash
   # Python 3
   python -m http.server 8000
   
   # Then visit http://localhost:8000 in your browser
   ```

   **Option 3: Using Node.js http-server**
   ```bash
   npx http-server -p 8000
   
   # Then visit http://localhost:8000 in your browser
   ```

   **Option 4: Using VS Code Live Server**
   - Install the "Live Server" extension in VS Code
   - Right-click on `index.html` and select "Open with Live Server"

## 📱 Responsive Breakpoints

- **Desktop**: 1024px and above
- **Tablet**: 768px - 1023px
- **Mobile**: 767px and below

## 🖼️ Image Sources

All images are sourced from [Pexels.com](https://www.pexels.com/), a free stock photo website:
- High-quality interior design photography
- Royalty-free for personal and commercial use
- No attribution required (but appreciated)

### Image Categories Used:
- Living Rooms
- Kitchens & Dining Areas
- Bedrooms
- Bathrooms
- Home Offices
- Commercial Spaces

## 🛠️ Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with Flexbox and Grid
- **JavaScript (ES6+)** - Interactive features and animations
- **Responsive Design** - Mobile-first approach
- **CSS Variables** - Maintainable color scheme
- **CSS Animations** - Smooth transitions and effects

## 📄 Pages Overview

### Home Page (`index.html`)
- Hero section with call-to-action
- About section with company introduction
- Featured services preview
- Portfolio highlights
- Call-to-action section

### Services Page (`services.html`)
- Comprehensive service listings (9 categories)
- Detailed service descriptions
- Design process overview (4 steps)
- Call-to-action for consultation

### Gallery Page (`gallery.html`)
- Organized portfolio showcase
- Categories: Living Rooms, Kitchens, Bedrooms, Bathrooms, Home Offices, Commercial
- Hover effects on images
- Responsive grid layout

### Contact Page (`contact.html`)
- Contact form with validation
- Business information (address, phone, email, hours)
- FAQ section
- Map placeholder
- Social media links

## ✨ Key Features Explained

### Mobile Navigation
- Hamburger menu for mobile devices
- Smooth slide-in animation
- Closes automatically when link is clicked
- Active page highlighting

### Scroll Animations
- Elements fade in as you scroll
- Intersection Observer API for performance
- Smooth transitions

### Form Handling
- Client-side validation
- User-friendly error messages
- Success notification
- Form reset after submission

### Hover Effects
- Service cards elevate on hover
- Gallery images zoom smoothly
- Navigation links animate
- Buttons have shadow effects

## 🔧 Customization

### Changing Colors
Edit the CSS variables in `css/styles.css`:
```css
:root {
    --primary-color: #2c3e50;
    --secondary-color: #d4af37;
    --accent-color: #8b7355;
    /* ... */
}
```

### Changing Content
- Edit HTML files directly to update text content
- Replace image URLs with your own images
- Update contact information in `contact.html`

### Adding New Pages
1. Create a new HTML file
2. Copy the header and footer from existing pages
3. Add your content
4. Update navigation links in all pages

## 📈 Performance Optimization

- Images loaded from CDN (Pexels)
- Minimal JavaScript usage
- CSS animations using GPU-accelerated properties
- Responsive images with appropriate sizes
- Optimized CSS with minimal redundancy

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📝 Future Enhancements

- [ ] Backend integration for contact form
- [ ] Blog section for design tips
- [ ] Client testimonials slider
- [ ] Before/after image comparisons
- [ ] Virtual tour functionality
- [ ] Multi-language support
- [ ] Dark mode toggle
- [ ] Interactive 3D room visualizer

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👤 Author

**Luxe Interiors Team**
- Website: [luxeinteriors.com](https://luxeinteriors.com)
- Email: info@luxeinteriors.com
- Phone: +1 (555) 123-4567

## 🙏 Acknowledgments

- Design inspiration from [We Three Design](https://www.wethreedesign.com/)
- Images from [Pexels.com](https://www.pexels.com/)
- Icons: Emoji-based for simplicity and universal support

## 📞 Support

For support, email info@luxeinteriors.com or visit our Contact page.

---

**Made with ❤️ by the Luxe Interiors Team**
