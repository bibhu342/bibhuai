# 🚀 Bibhudendu Behera Portfolio

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-green?logo=github)](https://bibhu342.github.io/bibhuai/)
[![HTML Validation](https://img.shields.io/badge/HTML-Valid-brightgreen?logo=w3c)](https://validator.w3.org/nu/?doc=https%3A%2F%2Fbibhu342.github.io%2Fbibhuai%2F)
[![Lighthouse](https://img.shields.io/badge/Lighthouse-100%2F100-brightgreen?logo=lighthouse)](https://github.com/bibhu342/bibhuai/actions)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

Professional portfolio showcasing data automation projects, Python engineering solutions, and CSV processing tools.

## 🌟 Features

- **Responsive Design**: Mobile-first approach with modern CSS Grid and Flexbox
- **SEO Optimized**: Complete meta tags, Open Graph, Twitter Cards, and JSON-LD structured data
- **Performance**: Lighthouse 100/100 scores, optimized assets, preconnect links
- **Accessibility**: WCAG 2.1 AA compliant, semantic HTML, screen reader friendly
- **Privacy-First**: GDPR-compliant cookie consent, analytics opt-in
- **Modern PWA**: Web manifest, favicon system, offline-ready

## 🛠 Technologies

- **Frontend**: HTML5, CSS3, Vanilla JavaScript
- **Deployment**: GitHub Pages with automated workflows
- **Analytics**: Google Analytics 4 (privacy-focused)
- **Forms**: Formspree integration for contact form
- **CI/CD**: GitHub Actions for validation, testing, and deployment

## 🚀 Quick Start

1. **Clone the repository**
   ```bash
   git clone https://github.com/bibhu342/bibhuai.git
   cd bibhuai
   ```

2. **Customize content**
   - Update personal information in `index.html`
   - Replace placeholder assets in `/assets/` folder
   - Configure Formspree form ID
   - Add Google Analytics tracking ID

3. **Deploy**
   ```bash
   git add .
   git commit -m "Customize portfolio"
   git push origin gh-pages
   ```

## 📁 Project Structure

```
bibhuai/
├── assets/
│   ├── images/             # Profile and project images
│   ├── favicon-16x16.png   # Favicon (16x16)
│   ├── favicon-32x32.png   # Favicon (32x32)
│   ├── apple-touch-icon.png # iOS home screen icon
│   ├── og-image.png        # Social media preview
│   └── Bibhudendu_Behera_Resume.pdf # Downloadable resume
├── css/
│   └── contrast-fix.css    # Dark mode accessibility fixes
├── data/
│   └── projects.json       # Project data
├── scripts/                # Build and utility scripts
├── .github/workflows/      # CI/CD automation
├── index.html             # Main portfolio page
├── 404.html               # Error page with SEO meta tags
├── privacy.html           # Privacy policy page
├── terms.html             # Terms of service page
├── site.webmanifest       # PWA configuration
├── robots.txt            # Search engine directives
├── sitemap.xml          # SEO sitemap (includes all pages)
├── feed.xml             # RSS feed for projects
└── README.md            # This file
```

## 🔧 Configuration

### Analytics Setup
1. Get Google Analytics 4 Measurement ID
2. Replace `G-XXXXXXX` in `index.html` with your ID
3. Commit changes to enable tracking

### Contact Form Setup
1. Create account at [Formspree.io](https://formspree.io)
2. Get your form endpoint ID
3. Replace `<YOUR_FORM_ID>` in `index.html`
4. Test form submission

### Custom Domain (Optional)
1. Add `CNAME` file with your domain
2. Configure DNS settings
3. Update GitHub Pages settings

## 🔄 Development Workflow

1. **Local Development**
   ```bash
   # Serve locally (Python)
   python -m http.server 8000
   
   # Or use any static server
   npx serve .
   ```

2. **Asset Generation**
   ```bash
   # Regenerate favicons
   python create_favicon.py
   
   # Update OG image (manual process)
   # Screenshot hero section at 1200x630
   ```

3. **Validation**
   ```bash
   # HTML validation runs automatically via GitHub Actions
   # Accessibility testing via Pa11y and Axe
   # Lighthouse CI for performance monitoring
   ```

## 📊 Performance Metrics

- **Lighthouse Performance**: 100/100
- **Lighthouse Accessibility**: 100/100
- **Lighthouse Best Practices**: 100/100
- **Lighthouse SEO**: 100/100
- **Core Web Vitals**: All Green

## 🔒 Privacy & Security

- **GDPR Compliant**: Cookie consent banner
- **Privacy-First Analytics**: IP anonymization, opt-in tracking
- **Secure Headers**: CSP, referrer policy, SRI integrity
- **No Third-Party Tracking**: Only first-party analytics when consented

## 🤝 Contributing

1. Fork the repository
2. Create feature branch (`git checkout -b feature/improvement`)
3. Commit changes (`git commit -am 'Add new feature'`)
4. Push to branch (`git push origin feature/improvement`)
5. Create Pull Request

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📞 Contact

- **Email**: [bibhu342@gmail.com](mailto:bibhu342@gmail.com)
- **LinkedIn**: [bibhudendu-behera](https://www.linkedin.com/in/bibhudendu-behera-b5375b5b)
- **GitHub**: [@bibhu342](https://github.com/bibhu342)

## 📝 Changelog

### [Unreleased]
- Enhanced SEO with comprehensive schema.org markup
- Added privacy-compliant analytics
- Implemented contact form with Formspree
- Added comprehensive CI/CD pipeline

### [1.0.1] - 2025-01-XX
- ✅ Fixed HTML DOCTYPE syntax errors in all HTML files
- ✅ Completed sitemap.xml with privacy.html and terms.html entries
- ✅ Added comprehensive SEO meta tags to 404.html (meta description, Open Graph, canonical URL)
- ✅ Improved HTML validation compliance

### [1.0.0] - 2025-11-13
- Initial portfolio launch
- Responsive design implementation
- SEO optimization
- GitHub Pages deployment

---

⭐ **Star this repository if you found it helpful!**
