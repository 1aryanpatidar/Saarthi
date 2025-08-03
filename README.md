# Saarthi - Your College Companion 🎓

A modern, mobile-first website for Saarthi - a student-run college brand that helps students buy academic essentials through WhatsApp + Google Form integration.

## 🌟 Features

- **Mobile-First Design**: Optimized for mobile users with responsive layout
- **Modern UI/UX**: Clean, minimalist design with smooth animations
- **WhatsApp Integration**: Direct WhatsApp deep links for instant communication
- **Google Forms Integration**: Seamless order collection
- **Bootstrap 5.3**: Latest Bootstrap framework for responsive design
- **Vanilla JavaScript**: Lightweight and fast performance
- **SEO Optimized**: Meta tags and structured content

## 🛠 Tech Stack

- **Frontend**: HTML5, CSS3, JavaScript (Vanilla)
- **Framework**: Bootstrap 5.3
- **Icons**: Font Awesome 6.4.0
- **Fonts**: Google Fonts (Poppins, Open Sans)
- **No Backend Required**: Static website

## 📁 File Structure

```
saarthi-website/
├── index.html          # Main HTML file
├── styles.css          # Custom CSS styles
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## 🚀 Quick Start

1. **Download/Clone** the files to your local machine
2. **Open** `index.html` in your web browser
3. **Customize** the content as needed (see customization guide below)
4. **Deploy** to your web hosting service

## ⚙️ Customization Guide

### 1. Update Contact Information

Replace `91XXXXXXXXXX` with your actual WhatsApp number in:
- `index.html` (all WhatsApp links)
- Update email and social media links in the footer

### 2. Update Google Form Links

Replace the placeholder Google Form links:
```html
<!-- Replace these URLs with your actual Google Form links -->
<a href="https://forms.google.com/your-form-link-1" target="_blank">
<a href="https://forms.google.com/your-form-link-2" target="_blank">
```

### 3. Update Product Images

Replace the placeholder images with actual product photos:
```html
<!-- Replace with actual calculator images -->
<img src="path/to/your/calculator-image.jpg" alt="CASIO FX-991ES Plus">
```

### 4. Customize Colors

The color scheme is defined in CSS variables in `styles.css`:
```css
:root {
    --primary-color: #3F51B5;    /* Indigo */
    --accent-color: #FFC107;     /* Amber */
    --background-color: #F9F9F9; /* Light Gray */
    --text-primary: #212121;     /* Dark Gray */
    --text-secondary: #616161;   /* Medium Gray */
}
```

### 5. Update Product Information

Modify product details in the Products section:
- Product names and descriptions
- Prices and features
- Taglines and badges

## 📱 Mobile Optimization

The website is optimized for mobile users with:
- Responsive design that works on all screen sizes
- Touch-friendly buttons and navigation
- Fast loading times for mobile networks
- Floating WhatsApp button for easy access

## 🔗 WhatsApp Integration

The website includes multiple WhatsApp integration points:
- Floating WhatsApp button (always visible)
- WhatsApp buttons in product cards
- WhatsApp CTA in hero section
- WhatsApp contact section

All WhatsApp links use the format:
```
https://wa.me/91XXXXXXXXXX?text=Hi%20Saarthi%2C%20I%20want%20to%20order%20a%20calculator
```

## 📊 Google Forms Integration

The website links to Google Forms for order collection:
1. Create Google Forms for each product
2. Replace the placeholder links in the HTML
3. Forms will collect customer information
4. Responses can be viewed in Google Sheets

## 🎨 Design Features

- **Modern Typography**: Poppins for headings, Open Sans for body text
- **Smooth Animations**: CSS animations and JavaScript interactions
- **Hover Effects**: Interactive elements with hover states
- **Loading States**: Visual feedback for user interactions
- **Accessibility**: Keyboard navigation and focus states

## 📈 Performance Features

- **Lightweight**: No heavy frameworks or libraries
- **Fast Loading**: Optimized images and minimal HTTP requests
- **Mobile Optimized**: Compressed assets for mobile networks
- **SEO Friendly**: Proper meta tags and semantic HTML

## 🚀 Deployment Options

### Option 1: GitHub Pages (Free)
1. Upload files to a GitHub repository
2. Enable GitHub Pages in repository settings
3. Your site will be available at `username.github.io/repository-name`

### Option 2: Netlify (Free)
1. Drag and drop the website folder to Netlify
2. Get a custom domain and SSL certificate
3. Automatic deployments from Git

### Option 3: Vercel (Free)
1. Connect your GitHub repository to Vercel
2. Automatic deployments on code changes
3. Custom domain and SSL included

### Option 4: Traditional Hosting
1. Upload files to your web hosting service
2. Configure domain and SSL certificate
3. Test all functionality

## 🔧 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📝 Customization Checklist

Before deploying, make sure to update:

- [ ] WhatsApp phone number
- [ ] Google Form links
- [ ] Product images
- [ ] Product prices and descriptions
- [ ] Contact information
- [ ] Social media links
- [ ] Company branding (if needed)
- [ ] Meta tags for SEO

## 🎯 Target Audience

- VNIT Nagpur students (especially 1st years)
- Engineering students across all branches
- Students looking for scientific calculators
- Mobile-first users

## 📞 Support

For technical support or customization help:
- Check the code comments for guidance
- Review the CSS variables for easy customization
- Test on multiple devices before deployment

## 📄 License

This project is created for Saarthi - Your College Companion. Feel free to modify and use for your own projects.

---

**Built with ❤️ for college students** 🎓

*Saarthi - Making college life easier, one calculator at a time!* 