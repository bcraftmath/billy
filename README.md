# NCFD Floors - Professional Epoxy Flooring Website

A modern, responsive website for NCFD Floors - North Carolina's premier epoxy flooring specialists.

## 🚀 Quick Start

This website is ready to deploy on GitHub Pages or any static hosting service.

### GitHub Pages Deployment

1. **Create a new GitHub repository**
   - Go to [GitHub](https://github.com) and create a new repository
   - Name it something like `ncfdfloors-website`
   - Make it public (required for free GitHub Pages)

2. **Upload your files**
   - Upload all files from the `ncfdfloors` folder to your repository
   - Make sure `index.html` is in the root directory

3. **Enable GitHub Pages**
   - Go to your repository settings
   - Scroll down to "Pages" section
   - Select "Deploy from a branch"
   - Choose "main" branch and "/ (root)"
   - Click Save

4. **Your site will be live at:**
   ```
   https://yourusername.github.io/repository-name
   ```

### Custom Domain Setup

Once your site is live on GitHub Pages, you can add a custom domain:

1. **Purchase domain** from registrar like:
   - Porkbun (recommended - developer friendly)
   - Namecheap
   - Cloudflare Registrar

2. **Configure DNS**
   - Add CNAME record pointing to: `yourusername.github.io`
   - Or A records pointing to GitHub Pages IPs

3. **Add domain to GitHub**
   - In repository settings > Pages
   - Add your custom domain (e.g., `ncfdfloors.com`)
   - Enable "Enforce HTTPS"

## 🎨 Features

- **Modern Bootstrap 5 Design** - Clean, professional appearance
- **Fully Responsive** - Works on all devices
- **SEO Optimized** - Proper meta tags and semantic HTML
- **Fast Loading** - Optimized for speed
- **Contact Form** - Interactive contact form with validation
- **Image Gallery** - Filterable portfolio gallery
- **Mobile Navigation** - Hamburger menu for mobile devices

## 📁 File Structure

```
ncfdfloors/
├── index.html          # Homepage
├── about.html          # About Us page
├── gallery.html        # Project gallery
├── contact.html        # Contact page
├── css/
│   └── custom.css      # Custom styles
└── README.md          # This file
```

## 🎯 Pages Overview

### Homepage (`index.html`)
- Hero section with call-to-action
- Services overview
- Why choose us section
- Call-to-action section

### About Us (`about.html`)
- Company story and experience
- Statistics and achievements
- What makes them different
- Process overview

### Gallery (`gallery.html`)
- Filterable project gallery
- Categories: Garage, Commercial, Industrial
- Interactive filter buttons
- Project descriptions

### Contact (`contact.html`)
- Contact information
- Interactive contact form
- FAQ section
- Service area information

## 🛠️ Customization

### Colors
Main colors can be changed in `css/custom.css`:
```css
:root {
    --primary-red: #d22f25;     /* Main brand color */
    --dark-bg: #161616;         /* Dark backgrounds */
    --light-gray: #f8f9fa;      /* Light sections */
    --text-muted: #6c757d;      /* Muted text */
}
```

### Contact Information
Update contact details in `contact.html`:
- Phone numbers
- Email addresses
- Service areas

### Content
All content can be easily updated by editing the HTML files. The structure is semantic and easy to follow.

## 🎪 Adding Real Images

To add real project photos:

1. Create an `images/` folder
2. Add your photos with descriptive names
3. Update the gallery placeholders with real images:
   ```html
   <img src="images/garage-project-1.jpg" class="gallery-image" alt="Garage floor project">
   ```

## 📞 Contact Form

The contact form includes:
- Client-side validation
- Professional styling
- Mobile-responsive design
- Success/error messaging

For production, you'll need to:
1. Add server-side form processing
2. Set up email notifications
3. Add spam protection (reCAPTCHA)

## 🔧 Technical Details

- **Bootstrap 5.3.0** - Modern CSS framework
- **Bootstrap Icons** - Icon library
- **Vanilla JavaScript** - No dependencies
- **Semantic HTML5** - Proper structure
- **CSS Grid & Flexbox** - Modern layouts

## 🌟 SEO Features

- Proper meta descriptions
- Open Graph tags for social sharing
- Semantic HTML structure
- Fast loading times
- Mobile-friendly design

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## 🎉 Ready to Launch!

Your professional NCFD Floors website is ready to go live. The clean, modern design will help showcase your 15+ years of experience and attract new customers.

Need help with deployment or customization? The code is clean and well-documented for easy modifications.

---

**NCFD Floors** - Turn your engine bay into a showroom! 🚗✨
