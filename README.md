# Alma Condolo - Artist Portfolio Website

A modern, responsive portfolio website for contemporary artist Alma Condolo. This website showcases her artwork across various mediums including paintings, sculptures, digital art, and installations.

## 🌟 Features

### Design & User Experience
- **Modern & Elegant Design**: Clean, professional layout with artistic flair
- **Fully Responsive**: Optimized for desktop, tablet, and mobile devices
- **Smooth Animations**: Subtle animations and transitions for enhanced user experience
- **Interactive Elements**: Hover effects, portfolio filtering, and dynamic content

### Sections
1. **Hero Section**: Eye-catching introduction with call-to-action
2. **About Section**: Artist biography and skills showcase
3. **Portfolio Gallery**: Filterable artwork collection with categories
4. **Contact Form**: Professional contact form with validation
5. **Social Media Integration**: Links to artist's social platforms

### Technical Features
- **Mobile-First Design**: Responsive navigation with hamburger menu
- **Portfolio Filtering**: Filter artwork by category (Paintings, Sculptures, Digital, Installations)
- **Smooth Scrolling**: Seamless navigation between sections
- **Form Validation**: Client-side validation for contact form
- **Performance Optimized**: Fast loading with optimized assets

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- No additional software required - runs entirely in the browser

### Installation
1. Download or clone the project files
2. Open `index.html` in your web browser
3. The website will load immediately with all functionality

### File Structure
```
alma-condolo-portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript functionality
└── README.md           # Project documentation
```

## 🎨 Customization

### Adding Artwork
To add new artwork to the portfolio:

1. **Add Portfolio Item**: In `index.html`, find the `.portfolio-grid` section
2. **Create New Item**: Add a new `.portfolio-item` div with the following structure:
   ```html
   <div class="portfolio-item" data-category="paintings">
       <div class="portfolio-image">
           <div class="artwork-placeholder">
               <i class="fas fa-paint-brush"></i>
           </div>
           <div class="portfolio-overlay">
               <h3>Artwork Title</h3>
               <p>Medium & Year</p>
           </div>
       </div>
   </div>
   ```

3. **Replace Placeholder**: Replace the `.artwork-placeholder` with an actual image:
   ```html
   <img src="path/to/your/artwork.jpg" alt="Artwork Title">
   ```

### Updating Content
- **Artist Information**: Modify the content in the About section
- **Contact Details**: Update email, phone, and location in the Contact section
- **Social Media**: Update social media links in the Contact section

### Styling Changes
- **Colors**: Modify CSS custom properties in `styles.css`
- **Fonts**: Change Google Fonts import in `index.html`
- **Layout**: Adjust grid layouts and spacing in `styles.css`

## 📱 Responsive Design

The website is fully responsive and optimized for:
- **Desktop**: 1200px+ (Full layout with side-by-side sections)
- **Tablet**: 768px - 1199px (Adjusted grid layouts)
- **Mobile**: < 768px (Single column layout, hamburger menu)

## 🛠️ Technologies Used

- **HTML5**: Semantic markup and structure
- **CSS3**: Modern styling with Flexbox and Grid
- **JavaScript (ES6+)**: Interactive functionality
- **Font Awesome**: Icons for artwork placeholders
- **Google Fonts**: Typography (Playfair Display & Inter)

## 🎯 Browser Support

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## 📧 Contact Form

The contact form includes:
- **Client-side Validation**: Required fields and email format validation
- **User Feedback**: Loading states and success messages
- **Responsive Design**: Optimized for all screen sizes

**Note**: The form currently simulates submission. To enable actual email sending, integrate with a backend service or email API.

## 🔧 Performance Features

- **Optimized Images**: Placeholder system for fast loading
- **Minimal Dependencies**: Only essential external resources
- **Efficient CSS**: Optimized selectors and minimal reflows
- **Smooth Animations**: Hardware-accelerated CSS transitions

## 📄 License

This project is created for Alma Condolo's portfolio. Feel free to use and modify for your own portfolio needs.

## 🤝 Contributing

To contribute to this project:
1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## 📞 Support

For questions or support regarding this portfolio website, please contact:
- Email: alma.condolo@email.com
- Phone: +1 (555) 123-4567

---

**Created with ❤️ for Alma Condolo's artistic vision**
