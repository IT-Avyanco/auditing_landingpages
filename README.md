# Avyanco Auditing - Landing Pages

Production-ready landing pages for Avyanco Auditing LLC with full HTML5 structure, responsive design, and analytics tracking.

## 📁 Directory Structure

```
landingpages/
├── dafza/
│   └── index.html          # DAFZA Auditors Landing Page
├── dmcc/
│   └── index.html          # DMCC Auditors Landing Page
├── general/
│   └── index.html          # General Auditors Landing Page
├── jafza/
│   └── index.html          # JAFZA Auditors Landing Page
├── .htaccess               # Server configuration (gzip, caching, security)
├── robots.txt              # SEO crawling rules
└── README.md               # This file
```

## 🚀 Features

### HTML5 Structure
- ✅ Complete HTML5 doctype and semantic markup
- ✅ Responsive viewport meta tags
- ✅ UTF-8 character encoding
- ✅ Mobile-first responsive design
- ✅ Fast scroll behavior

### SEO & Meta Tags
- ✅ Comprehensive meta descriptions
- ✅ Keywords optimized for each page
- ✅ Open Graph tags for social media sharing
- ✅ Twitter Card meta tags
- ✅ Schema.org structured data (JSON-LD)
- ✅ Optimized page titles

### Performance
- ✅ GZIP compression enabled (.htaccess)
- ✅ Browser caching headers
- ✅ Minified inline CSS
- ✅ Lazy-loaded images
- ✅ Fast image formats (WebP support)

### Analytics & Tracking
- ✅ Google Analytics 4 event tracking
- ✅ CTA click tracking
- ✅ Form submission tracking
- ✅ Contact link tracking
- ✅ Service card interaction tracking

### Responsive Design
- ✅ Mobile-first approach
- ✅ Flexible grid layouts
- ✅ Responsive typography (clamp)
- ✅ Touch-friendly buttons and links
- ✅ Optimized for phones, tablets, and desktops

### Security
- ✅ X-UA-Compatible headers
- ✅ X-Content-Type-Options protection
- ✅ X-Frame-Options (clickjacking protection)
- ✅ X-XSS-Protection headers
- ✅ Referrer-Policy configured
- ✅ Permissions-Policy restrictions

### Browsers
- ✅ Modern browsers (Chrome, Firefox, Safari, Edge)
- ✅ Internet Explorer 11+ support
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 🔧 Installation & Deployment

### Direct Upload
1. Download all files from this repository
2. Upload to your hosting provider
3. No additional build process needed - files are production-ready

### Apache/Shared Hosting
1. Upload `.htaccess` file to enable caching and gzip compression
2. Upload `robots.txt` for SEO crawling configuration
3. Upload HTML files to your domain
4. Ensure mod_rewrite and mod_deflate are enabled on your server

### Custom Domain Setup
1. Point your domain to the hosting server
2. Upload files to the publicly accessible folder
3. Ensure `.htaccess` is uploaded (might be hidden by default)

## 📊 Analytics Integration

All pages include Google Analytics 4 event tracking for:

**Events Tracked:**
- `contact_cta`: Header contact buttons (call, WhatsApp)
- `cta_click`: Call-to-action buttons throughout the page
- `contact_cta`: Contact links (phone, email, WhatsApp)
- `form_view`: Consultation form loaded
- `form_submit`: Form submitted successfully

**Requirements:**
- GA4 must be configured on your WordPress site or hosting
- `gtag` script must be loaded globally

## 📱 Responsive Breakpoints

The pages are optimized for:
- **Mobile**: 320px - 480px
- **Tablet**: 481px - 768px
- **Desktop**: 769px - 1200px
- **Large Desktop**: 1201px+

## 🎨 Customization

### Update Meta Information
Edit the `<meta>` tags in the `<head>` section of each HTML file:
```html
<meta name="description" content="Your custom description">
<meta property="og:title" content="Your custom title">
```

### Update Contact Information
Search and replace contact details:
- **Phone**: +971 50 398 9000
- **Email**: info@avyanco.com
- **WhatsApp**: https://wa.me/97142405000

### Update Images/Links
Replace image URLs and links as needed throughout the pages.

### Add More Content
Add new sections following the existing CSS classes and structure.

## 🔐 Security Checklist

Before deployment:
- ✅ Verify `.htaccess` is uploaded
- ✅ Test HTTPS/SSL certificate
- ✅ Enable gzip compression
- ✅ Configure caching headers
- ✅ Test on mobile devices
- ✅ Verify Google Analytics tracking

## 📈 Performance Tips

1. **Images**: Use optimized, compressed images
2. **CDN**: Use a CDN for faster global delivery
3. **Cache**: Leverage browser caching (configured in .htaccess)
4. **Compression**: Ensure gzip is enabled on server
5. **Loading**: All resources load from trusted CDNs

## 🗂️ File Sizes

- **dafza/index.html**: ~160 KB
- **dmcc/index.html**: ~160 KB
- **general/index.html**: ~152 KB
- **jafza/index.html**: ~159 KB
- **.htaccess**: ~2 KB
- **robots.txt**: ~1 KB

## 📞 Contact Information

**Avyanco Auditing LLC**
- Phone: +971 50 398 9000
- Email: info@avyanco.com
- Website: https://avyanco.net
- WhatsApp: +971 4 240 5000

## 🐛 Troubleshooting

### Pages not displaying correctly
- Clear browser cache (Ctrl+Shift+Del)
- Ensure all images are loading properly
- Check browser console for JavaScript errors

### Forms not submitting
- Verify Zoho Form URL is still valid
- Check browser's Network tab for blocked requests
- Ensure CORS policies allow form submissions

### Performance slow
- Enable GZIP compression in .htaccess
- Minimize external requests
- Use browser caching (configured in .htaccess)

## 📄 License & Attribution

These landing pages are created for Avyanco Auditing LLC.
All content and design are proprietary.

---

**Last Updated**: April 21, 2026
**Version**: 1.0
