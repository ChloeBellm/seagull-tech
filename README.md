# Seagull Tech Solutions Website

A modern, professional one-page website for Seagull Tech Solutions, built with Tailwind CSS.

## Features

### Design
- **Modern, clean aesthetic** with fresh emerald green (#10b981) brand color
- **Responsive layout** - mobile-first design that works on all devices
- **Custom typography** - Montserrat for headings, Inter for body text
- **Smooth animations** - hover effects and transitions throughout

### Sections
1. **Hero Section** - Bold headline with dual CTAs
2. **Services** - Three service cards with technology tags
3. **About** - Company overview with key differentiators
4. **Contact** - Full contact form with validation
5. **Footer** - Copyright and email link

### Accessibility
- ✅ Skip to main content link
- ✅ Semantic HTML with proper landmarks
- ✅ ARIA labels on interactive elements
- ✅ Keyboard navigation support
- ✅ Focus states on all interactive elements
- ✅ Descriptive alt text on images

### SEO
- ✅ Meta description
- ✅ Open Graph tags for social sharing
- ✅ Twitter Card tags
- ✅ Semantic HTML structure
- ✅ Descriptive page title

### Technical
- **Tailwind CSS** - Utility-first CSS framework via CDN
- **Inline SVG icons** - No external icon library dependency
- **Mobile navigation** - Hamburger menu for small screens
- **Custom brand colors** configured in Tailwind
- **Optimized fonts** - Preconnected to Google Fonts

## Setup

### Contact Form
The contact form requires configuration before it will work:

1. Sign up for a free account at [Formspree](https://formspree.io/)
2. Create a new form and get your form ID
3. Update line 276 in `index.html`:
   ```html
   <form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
   ```

### Deployment
This is a static site that can be hosted anywhere:
- **Vercel** - Connect your GitHub repo for automatic deployments
- **Netlify** - Drag and drop the files or connect GitHub
- **GitHub Pages** - Enable in repository settings
- Any static hosting service

## Files

- `index.html` - Main website file
- `logo.png` - Company logo (icon only, transparent background)
- `favicon.svg` - SVG favicon for modern browsers
- `README.md` - This file

## Color Palette

- **Primary Green**: #10b981 (Emerald)
- **Dark Green**: #059669 (Hover states)
- **Dark Navy**: #0f172a (Headers, dark backgrounds)
- **Slate**: #1e293b (Secondary dark)

## Technology Stack

### Highlighted Technologies
**Data Engineering:**
- Python
- Apache Airflow
- dbt
- AI/ML

**SRE:**
- Kubernetes
- Terraform
- Grafana

**Cloud:**
- AWS
- GCP
- Docker

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Future Improvements

Consider adding:
- Client testimonials
- Case studies / portfolio
- Blog or resources section
- Google Analytics or privacy-friendly alternative
- Performance monitoring
- Progressive Web App (PWA) features

## License

© 2026 Seagull Tech Solutions. All rights reserved.

## Contact

hello@seagulltech.co.uk
