# Standalone Portfolio Website

This is a complete, standalone portfolio website that you can host anywhere. It's built with pure HTML, CSS (Tailwind), and JavaScript - no build process required!

## Features

- ✅ Fully responsive design
- ✅ Modern animations and hover effects
- ✅ Working contact form (frontend validation)
- ✅ Project showcase with modal details
- ✅ Skills section with progress bars
- ✅ Smooth scrolling navigation
- ✅ Mobile-friendly navigation menu
- ✅ Professional design with purple/indigo theme

## How to Use

1. **Upload to your hosting**: Simply upload the `index.html` file to your web server
2. **Access via URL**: The portfolio will be accessible at your domain/subdirectory
3. **Customize content**: Edit the HTML file to update:
   - Personal information (name, bio, contact details)
   - Skills and technologies
   - Project information and images
   - Social media links

## What You Need to Update

### Personal Information
- Line 27: Change "Alex Johnson" to your name
- Line 29: Update your title/role
- Lines 37-40: Update your bio description
- Lines 86-106: Update contact information (email, phone, location)

### Projects
- Lines 284-410: Update project information in the HTML
- Lines 470-520: Update project data in the JavaScript object

### Skills
- Lines 227-280: Update the skills section with your technologies

### Social Links
- Update all `href="#"` attributes with your actual social media profiles

## Hosting Options

You can host this on:
- **Your own server**: Upload to any web hosting service
- **GitHub Pages**: Free hosting for static sites
- **Netlify**: Free static site hosting with drag-and-drop deployment
- **Vercel**: Free hosting with automatic deployments
- **Any shared hosting provider**: Most support static HTML files

## File Structure

```
standalone-portfolio/
├── index.html          # Complete portfolio website
└── README.md          # This file
```

## Technical Details

- **No dependencies**: Uses CDN links for Tailwind CSS and Font Awesome
- **No build process**: Ready to upload and use
- **Lightweight**: Single HTML file under 50KB
- **Fast loading**: Optimized images and minimal external resources
- **SEO ready**: Proper meta tags and semantic HTML

## Contact Form

The contact form includes:
- Frontend validation
- Clean, professional styling
- Success/error messaging
- All form fields (name, email, subject, message)

**Note**: To make the contact form actually send emails, you'll need to:
1. Set up a backend service (like Formspree, Netlify Forms, or your own server)
2. Update the form action in the JavaScript `handleContactForm` function

## Browser Support

Works in all modern browsers:
- Chrome 60+
- Firefox 60+
- Safari 12+
- Edge 79+

## License

Feel free to use this template for your own portfolio. No attribution required.
