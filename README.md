# Indigo Gutter Cleaning Website

A professional, SEO-optimized website for Indigo Gutter Cleaning in Kalispell, Montana.

## 🌟 Features

- **Responsive Design**: Mobile-first design that works on all devices
- **SEO Optimized**: Meta tags, semantic HTML, and proper heading structure
- **Modern UI**: Built with Tailwind CSS for a clean, professional look
- **Contact Form**: Functional contact form with validation
- **Fast Loading**: Uses CDN for Tailwind CSS and Font Awesome icons

## 📄 Pages

1. **Home Page** (`index.html`)
   - Hero section with call-to-action
   - Services overview
   - Why choose us section
   - Contact CTA

2. **Services Page** (`services.html`)
   - Detailed service descriptions
   - Residential & commercial offerings
   - Why regular cleaning matters

3. **About Page** (`about.html`)
   - Meet Jamin Brown (owner)
   - Personal story and commitment
   - Why choose Indigo

4. **Contact Page** (`contact.html`)
   - Contact form with validation
   - Business information
   - Service areas
   - Emergency service notice

## 🚀 Getting Started

### Option 1: Open Locally
Simply open `index.html` in your web browser to view the site.

### Option 2: Use a Local Server
For better testing, use a local development server:

**Python:**
```bash
python -m http.server 8000
```

**Node.js (with npx):**
```bash
npx serve
```

Then visit `http://localhost:8000` in your browser.

## 🎨 Customization

### Colors
The site uses an indigo/purple color scheme. To change colors, modify the Tailwind classes:
- `bg-indigo-600` - Primary buttons and CTAs
- `text-indigo-600` - Links and accents
- `hero-gradient` - Hero section gradient (edit in `<style>` tag)

### Contact Information
Update placeholder contact details in all pages:
- Phone: `(406) 555-0123`
- Email: `info@indigogutter.com`
- Address: Update service area locations

### Images
To add images:
1. Create an `images` folder
2. Add your photos
3. Replace icon sections with `<img>` tags

Example:
```html
<img src="images/hero-image.jpg" alt="Gutter cleaning in Kalispell">
```

### Form Integration
The contact form currently shows a success message on submit. To make it functional:

#### Option 1: FormSubmit (Free)
Add to form action:
```html
<form action="https://formsubmit.co/your@email.com" method="POST">
```

#### Option 2: Netlify Forms
Add `data-netlify="true"` to form tag:
```html
<form data-netlify="true">
```

#### Option 3: Backend Service
Integrate with your preferred backend (PHP, Node.js, etc.)

## 📱 SEO Features

- Semantic HTML5 structure
- Meta descriptions on all pages
- Open Graph tags for social sharing
- Descriptive alt texts (when images added)
- Local SEO keywords (Kalispell, Montana)
- Mobile-responsive design
- Fast load times

## 🔧 Technologies Used

- **HTML5**: Semantic markup
- **Tailwind CSS**: Utility-first CSS framework (via CDN)
- **Font Awesome**: Icon library (via CDN)
- **JavaScript**: Mobile menu and form handling

## 📦 Deployment

### GitHub Pages
1. Push to GitHub repository
2. Go to Settings > Pages
3. Select branch and save

### Netlify
1. Drag and drop the folder to Netlify
2. Or connect your GitHub repository

### Traditional Hosting
Upload files via FTP to your web host's public_html or www directory

## ✅ Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## 📝 To-Do Before Launch

- [ ] Replace placeholder phone number
- [ ] Replace placeholder email address
- [ ] Add real business photos
- [ ] Set up contact form backend
- [ ] Add Google Analytics (optional)
- [ ] Register domain name
- [ ] Set up business email
- [ ] Test all forms and links
- [ ] Add Google Business Profile link
- [ ] Create social media links (optional)

## 📞 Need Help?

For questions or customization help, consider:
- Hiring a web developer for custom features
- Using online resources like MDN Web Docs
- Exploring Tailwind CSS documentation

---

**Built for Indigo Gutter Cleaning** - Serving Kalispell, Montana and surrounding areas.
