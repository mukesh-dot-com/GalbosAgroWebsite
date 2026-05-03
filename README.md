# Galbos Agro Website

A professional, responsive website for Galbos Agro - an agricultural company focused on procurement, supply chain management, quality assurance, farmer support, and sustainable agriculture practices.

## 🎨 Features

- **Modern Design**: Green and gold color scheme representing agriculture and prosperity
- **Responsive Layout**: Works seamlessly on desktop, tablet, and mobile devices
- **Professional Structure**: Similar to Altrasol, with comprehensive sections
- **User-Friendly Navigation**: Easy-to-use menu system with mobile hamburger menu
- **Contact Forms**: Functional contact form with validation
- **SEO-Friendly**: Semantic HTML structure

## 📁 Project Structure

```
Galbos Agro Website/
├── index.html           # Home page
├── about.html           # About Us page
├── services.html        # Services/Verticals page
├── contact.html         # Contact page
├── css/
│   └── style.css        # All styling (green & gold theme)
├── js/
│   └── script.js        # Interactive features
├── images/              # Folder for images (add your photos here)
└── README.md           # This file
```

## 🚀 How to Use

### 1. Open the Website
Simply open `index.html` in your web browser to view the website locally.

### 2. View Different Pages
- **Home**: `index.html` - Main landing page with overview
- **About**: `about.html` - Company mission, values, and story
- **Services**: `services.html` - Detailed service offerings
- **Contact**: `contact.html` - Contact form and information

### 3. Add Your Images
Place your company images in the `images/` folder and reference them in the HTML files. For example:
```html
<img src="images/your-image.jpg" alt="Description">
```

## 🎯 Pages Overview

### Home Page (index.html)
- Hero section with company tagline
- Feature highlights (Technology, Farmers, Quality, Pan India)
- Services overview
- Impact statistics
- About preview
- Call-to-action section

### About Page (about.html)
- Company story
- Mission statement
- Core values
- Benefits list

### Services Page (services.html)
- Detailed service descriptions:
  - Procurement & Supply Chain
  - Quality Assurance
  - Farmer Support & Development
  - Sustainable Agriculture
- Why choose us section

### Contact Page (contact.html)
- Contact information
- Contact form with validation
- Social media links
- Business hours

## 🎨 Color Scheme

- **Primary Green**: #1b5e20 (Trust & Nature)
- **Light Green**: #2e7d32 (Growth)
- **Gold**: #f39c12 (Prosperity)
- **Light Gold**: #f8b739 (Accent)

## 📱 Responsive Design

The website is fully responsive and works on:
- Desktop computers (1200px+)
- Tablets (768px - 1199px)
- Mobile phones (< 768px)

## ✨ Features Included

1. **Sticky Navigation** - Navigation bar stays at top while scrolling
2. **Mobile Menu** - Hamburger menu for mobile devices
3. **Form Validation** - Contact form with email validation
4. **Smooth Scrolling** - Smooth scroll animations
5. **Hover Effects** - Interactive button and card hover states
6. **Scroll Animations** - Elements fade in as user scrolls

## 🔧 Customization

### To Update Company Information:
1. Find and replace `Galbos Agro` with your company name (if needed)
2. Update contact details in all HTML files:
   - Phone: 987654321
   - Email: galbosagro@gmail.com
   - Address: 17th Cross, Manasa Layout

### To Change Colors:
Edit the CSS variables in `css/style.css`:
```css
:root {
    --primary-green: #1b5e20;
    --light-green: #2e7d32;
    --gold: #f39c12;
    --light-gold: #f8b739;
}
```

### To Add More Services:
Edit `services.html` and add new service detail cards following the existing structure.

## 📧 Contact Form

The contact form includes:
- Name field (required)
- Email field (required with validation)
- Phone field (optional)
- Subject field (required)
- Message field (required)

Note: In the current version, form data is logged to browser console. To send emails, integrate with a backend service like:
- Formspree
- EmailJS
- Your own server

## 🌐 Deployment

To host this website online:

1. **GitHub Pages**:
   - Upload files to GitHub
   - Enable GitHub Pages in settings
   - Your site will be live at `yourusername.github.io`

2. **Web Hosting**:
   - Upload files to hosting server via FTP
   - Ensure `index.html` is in root directory

3. **Local Server**:
   - For development, use Python: `python -m http.server 8000`
   - Or use VS Code Live Server extension

## 📝 Notes

- All images should be replaced with your company's actual images
- The contact form currently doesn't send emails; integrate with a backend service
- Consider adding a blog or news section for future updates
- SEO can be improved by adding meta descriptions and keywords to each page

## 🤝 Support

If you need modifications or have questions, feel free to reach out!

---

**Last Updated**: May 1, 2026
**Created for**: Galbos Agro
**Theme**: Green & Gold - Agriculture Excellence
