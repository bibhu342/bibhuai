# Contributing to Bibhudendu Behera Portfolio

Thank you for your interest in contributing to this portfolio project! This guide will help you understand how to contribute effectively.

## 🚀 Quick Start

1. **Fork the repository**
2. **Clone your fork**
   ```bash
   git clone https://github.com/YOUR_USERNAME/bibhu-portfolio.git
   cd bibhu-portfolio
   ```
3. **Create a feature branch**
   ```bash
   git checkout -b feature/your-feature-name
   ```

## 📋 Development Setup

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Python 3.8+ (for scripts and validation)
- Node.js 18+ (for CI tools, optional for local development)

### Local Development
```bash
# Serve locally using Python
python -m http.server 8000

# Or using Node.js
npx serve .

# Access at http://localhost:8000
```

## 🔍 Pull Request Checklist

Before submitting a PR, please ensure:

### ✅ Code Quality
- [ ] HTML validates against W3C standards
- [ ] CSS follows modern best practices
- [ ] JavaScript is vanilla (no frameworks) and ES6+
- [ ] All links work and open appropriately
- [ ] Images have proper alt text

### ✅ Performance
- [ ] Images are optimized (PNG/WebP for photos, SVG for icons)
- [ ] No inline styles (use CSS classes)
- [ ] Minimal JavaScript for enhanced functionality
- [ ] Lighthouse score remains 95+ across all metrics

### ✅ Accessibility
- [ ] Semantic HTML structure
- [ ] Proper heading hierarchy (h1 → h2 → h3)
- [ ] Sufficient color contrast (4.5:1 minimum)
- [ ] Keyboard navigation works
- [ ] Screen reader friendly

### ✅ SEO & Social
- [ ] Meta tags updated if content changes
- [ ] Open Graph image regenerated if needed
- [ ] Sitemap updated for new pages
- [ ] JSON-LD structured data maintained

### ✅ Testing
- [ ] Manual testing on mobile and desktop
- [ ] Cross-browser compatibility verified
- [ ] Form submissions work (if applicable)
- [ ] All CI checks pass

## 🧪 Running Tests Locally

### HTML Validation
```bash
# Install validator (one-time setup)
npm install -g html-validate

# Validate HTML
html-validate index.html
```

### Accessibility Testing
```bash
# Install Pa11y (one-time setup)
npm install -g pa11y

# Test accessibility
pa11y http://localhost:8000
```

### Performance Testing
```bash
# Install Lighthouse CLI (one-time setup)
npm install -g lighthouse

# Run Lighthouse
lighthouse http://localhost:8000 --view
```

## 📁 Project Structure

```
bibhu-portfolio/
├── assets/           # Images, favicons, resume
├── scripts/         # Build and utility scripts
├── .github/         # GitHub workflows and config
├── index.html       # Main portfolio page
├── site.webmanifest # PWA configuration
├── robots.txt       # Search engine directives
└── sitemap.xml      # SEO sitemap
```

## 🎨 Design Guidelines

### Visual Design
- **Color Scheme**: Dark theme with blue accents (#3b82f6)
- **Typography**: System fonts (-apple-system, BlinkMacSystemFont, 'Segoe UI')
- **Layout**: Mobile-first responsive design
- **Spacing**: Consistent 8px grid system

### Content Guidelines
- **Tone**: Professional but approachable
- **Structure**: Clear hierarchy and scannable content
- **Links**: Descriptive anchor text, external links open in new tabs
- **Images**: High-quality, properly sized, optimized

## 🔧 Common Tasks

### Adding a New Project
1. Add a `project-card` article to the Projects section in `index.html`
2. Add a 800×450 image (PNG + WebP) to `assets/images/projects/`
3. Test locally with `python3 -m http.server`
4. Commit changes

### Updating Assets
1. Add/modify files in `assets/`
2. Optimize images (use tools like ImageOptim, TinyPNG)
3. Update references in HTML/CSS
4. Test on local server
5. Commit changes

### Modifying Workflows
1. Edit files in `.github/workflows/`
2. Test workflow syntax using GitHub Actions validator
3. Monitor workflow runs after PR merge

## 🐛 Bug Reports

When reporting bugs, please include:

- **Browser and version**
- **Device type** (desktop/mobile/tablet)
- **Steps to reproduce**
- **Expected vs actual behavior**
- **Screenshots** (if visual issue)
- **Console errors** (if JavaScript issue)

## 💡 Feature Requests

For new features, please:

1. **Check existing issues** to avoid duplicates
2. **Describe the use case** and user benefit
3. **Consider maintainability** and project scope
4. **Provide mockups/examples** if applicable

## 📝 Commit Messages

Follow conventional commit format:

```
type(scope): description

feat: add new project showcase section
fix: resolve mobile navigation issue  
docs: update README with new instructions
style: improve button hover animations
refactor: reorganize CSS structure
test: add accessibility tests
chore: update dependencies
```

## 🔒 Security

- **Never commit secrets** (API keys, tokens, passwords)
- **Use environment variables** for sensitive configuration
- **Validate user inputs** in forms
- **Keep dependencies updated** via Dependabot

## 📞 Questions?

- **Open an issue** for technical questions
- **Email**: bibhu342@gmail.com for direct communication
- **Review existing issues** and discussions first

## 🎉 Recognition

Contributors will be acknowledged in:
- Repository contributors list
- Project documentation
- Release notes (for significant contributions)

---

Thank you for contributing to make this portfolio better! 🚀