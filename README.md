# شركة النعّاس للأثاث والستائر - Alnaas Furniture & Curtains

A professional single-page website for a Libyan furniture and curtains company, built with pure HTML, CSS, and JavaScript.

## 🌟 Features

- **Fully Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Modern UI**: Clean, professional design with beige, gold, and light gray color palette
- **Arabic Support**: RTL layout with Arabic-friendly fonts (Cairo)
- **Smooth Animations**: Scroll-triggered fade-in animations for sections
- **Interactive Gallery**: Hover effects on furniture and curtains images
- **Quote Request Form**: Popup modal for customers to request quotes
- **Mobile Menu**: Responsive navigation for mobile devices
- **Accessibility**: Keyboard navigation and focus management
- **Performance Optimized**: Lazy loading, debounced scroll events

## 📁 File Structure

```
ALNAAS/
├── index.html          # Main HTML file
├── css/
│   └── style.css       # All styles and responsive design
├── js/
│   └── script.js       # Interactive functionality
├── images/             # Folder for custom images (optional)
└── README.md          # This file
```

## 🚀 Deployment to GitHub Pages

### Method 1: Using GitHub Web Interface

1. Create a new repository on GitHub
2. Upload all files (index.html, css/, js/, images/)
3. Go to repository **Settings** → **Pages**
4. Under "Source", select `main` branch and `/ (root)` folder
5. Click **Save**
6. Your site will be live at: `https://yourusername.github.io/repository-name`

### Method 2: Using Git Command Line

```bash
# Navigate to your project folder
cd c:/Users/HP/Desktop/ALNAAS

# Initialize git repository
git init

# Add all files
git add .

# Commit files
git commit -m "Initial commit: Alnaas Furniture & Curtains website"

# Add remote repository (replace with your GitHub repo URL)
git remote add origin https://github.com/yourusername/alnaas-furniture.git

# Push to GitHub
git branch -M main
git push -u origin main

# Enable GitHub Pages in repository settings
```

## 🎨 Customization

### Colors
Edit the CSS variables in `css/style.css`:
```css
:root {
    --primary-gold: #D4AF37;
    --secondary-beige: #F5E6D3;
    --dark-beige: #E8D7C3;
    --light-gray: #F8F9FA;
    --dark-gray: #6C757D;
}
```

### Contact Information
Update contact details in `index.html` under the contact section:
- Phone: `+218 91 234 5678`
- Email: `info@alnaas.com`
- Address: `طرابلس – شارع الجرابة`

### Images
The site currently uses placeholder images from Unsplash. To use your own images:

1. Add your images to the `images/` folder
2. Update image sources in `index.html`:
   ```html
   <img src="images/your-image.jpg" alt="Description">
   ```

### Hero Background
Change the hero section background in `css/style.css`:
```css
.hero {
    background: linear-gradient(...), url('images/your-hero-image.jpg');
}
```

## 📱 Sections

1. **Header**: Company logo and navigation
2. **Hero**: Welcome section with call-to-action
3. **About**: Company information and features
4. **Gallery**: 6 furniture/curtain images with hover effects
5. **Contact**: Phone, email, address, and quote request button
6. **Footer**: Copyright information

## 🔧 Technical Details

- **No Dependencies**: Pure HTML, CSS, and JavaScript (no frameworks)
- **Font**: Google Fonts - Cairo (Arabic-friendly)
- **Images**: Currently using Unsplash placeholders
- **Browser Support**: Modern browsers (Chrome, Firefox, Safari, Edge)
- **Mobile-First**: Responsive breakpoints at 768px and 480px

## 📝 Quote Request Feature

The "Request Quote" button opens a modal form that collects:
- Full Name (الاسم الكامل)
- Phone Number (رقم الهاتف)

Currently, form data is logged to the console. To implement backend functionality:
1. Set up a backend API (e.g., Node.js, PHP, Python)
2. Update the `submitQuote()` function in `js/script.js`
3. Send form data via AJAX/Fetch API to your backend

## 🌐 Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📄 License

© 2025 شركة النعّاس للأثاث والستائر. All rights reserved.

## 🤝 Support

For any questions or support:
- Email: info@alnaas.com
- Phone: +218 91 234 5678
- Address: طرابلس – شارع الجرابة، ليبيا

---

**Made with ❤️ for Alnaas Furniture & Curtains**
