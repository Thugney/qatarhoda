# NordCloud Qatar Website

Modern, bilingual (English/Arabic) landing page for Microsoft 365 consulting services in Qatar.

## 🎨 Design Philosophy

This website follows a **clean, minimalist design system** focused on:

- **Simplicity**: Typography-driven design with generous whitespace
- **Professionalism**: Refined color palette and professional SVG icons
- **Accessibility**: Full keyboard navigation, screen reader support, and WCAG compliance
- **Performance**: Single-page HTML with optimized CSS, no external dependencies
- **Bilingual Excellence**: True RTL support with culturally-aware design patterns

## 🚀 Features

### Design System

**Color Palette**
- Primary: `#0066FF` (Professional blue)
- Accent: `#10B981` (Emerald for CTAs)
- Neutrals: Gray scale from 900 to 50
- Clean, intentional color usage throughout

**Typography**
- English: Inter (400, 600, 700 weights)
- Arabic: Tajawal (400, 500, 700, 800 weights)
- Responsive font sizing with clamp()
- Optimized line heights for readability

**Components**
- Border-first card design
- Subtle, layered shadows
- Professional SVG icons (Heroicons-style)
- Fast micro-interactions (200ms)
- Smooth scroll animations

### Bilingual Support

**Language Switching**
- Toggle between English and Arabic
- Persistent language preference (localStorage)
- Auto-detection based on browser language
- True RTL layout mirroring for Arabic
- Separate line-heights optimized per language

### SEO Optimization

**Meta Tags**
- Comprehensive Open Graph tags
- Twitter Card support
- Multilingual hreflang tags
- Local Business Schema markup
- Qatar-specific keywords

**SEO Targets**
- Microsoft 365 Qatar
- Intune Qatar
- Autopilot Qatar
- Defender XDR Qatar
- NordCloud Qatar

### Accessibility

**WCAG 2.1 Compliance**
- Semantic HTML5 structure
- ARIA labels on interactive elements
- Keyboard navigation support (Tab, Enter)
- Focus visible states
- Reduced motion support
- High contrast mode support
- Print-friendly styles

### Performance

**Optimizations**
- Zero JavaScript dependencies
- Embedded CSS (no external stylesheets)
- Optimized Google Fonts loading
- Intersection Observer for scroll animations
- Minimal DOM manipulation
- Efficient event delegation

## 📁 Project Structure

```
qatarhoda/
├── index.html          # Main website (1170 lines)
├── README.md           # This file
└── .git/               # Git repository
```

## 🛠️ Tech Stack

- **HTML5**: Semantic markup
- **CSS3**: Custom properties (CSS variables), Grid, Flexbox
- **Vanilla JavaScript**: No frameworks, pure DOM API
- **Google Fonts**: Inter (EN) + Tajawal (AR)

## 🎯 Target Audience

**Primary Markets**
- International schools in Doha
- Medical clinics in Qatar
- Qatar enterprises
- Government organizations

**Service Offerings**
- Microsoft Intune & Autopilot deployment
- Defender XDR security assessments
- Entra ID (Azure AD) optimization
- Microsoft 365 consulting

## 📦 Service Packages

### 1. Intune + Autopilot Jumpstart
**50,000 QAR / 30 days**
- Zero-touch enrollment for 300 devices
- Compliance & security policies
- Application deployment automation
- Bilingual documentation & training

### 2. Defender XDR Security Assessment ⭐
**40,000 QAR / 21 days**
- Security baseline assessment
- Conditional Access design
- Incident response playbook
- Bilingual security report

### 3. Entra ID Optimization
**30,000 QAR / 14 days**
- License waste analysis
- Identity governance setup
- Privileged access management
- Cost optimization report

## 🌐 Deployment

### Quick Start

1. **Clone the repository**
   ```bash
   git clone https://github.com/Thugney/qatarhoda.git
   cd qatarhoda
   ```

2. **Open locally**
   ```bash
   # Option 1: Direct open
   open index.html

   # Option 2: Simple HTTP server
   python3 -m http.server 8000
   # Visit http://localhost:8000
   ```

3. **Deploy to production**
   - Upload `index.html` to any web host
   - Works with GitHub Pages, Netlify, Vercel, or traditional hosting
   - No build process required

### Hosting Recommendations

**Static Hosting**
- [Netlify](https://netlify.com) - Drag & drop deployment
- [Vercel](https://vercel.com) - Git integration
- [GitHub Pages](https://pages.github.com) - Free with GitHub repo
- Traditional web hosting (cPanel, etc.)

**Custom Domain Setup**
```
nordcloud.qa → Configure DNS A/CNAME records
```

## 🔧 Customization

### Update Contact Information

Replace placeholder phone numbers in `index.html`:

```html
<!-- Find and replace: -->
+974XXXXXXXX → Your actual phone number
```

### Modify Service Packages

Edit pricing in the packages section (lines 872-948):

```html
<div class="price">
    50,000 QAR  <!-- Update amount -->
    <span class="price-period lang-en">30 days</span>
</div>
```

### Adjust Colors

Modify CSS variables in `:root` (lines 78-112):

```css
:root {
    --primary: #0066FF;      /* Your brand color */
    --accent: #10B981;       /* Your CTA color */
    /* ... */
}
```

### Add Analytics

Insert before closing `</head>` tag:

```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_MEASUREMENT_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_MEASUREMENT_ID');
</script>
```

## 🧪 Testing Checklist

- [ ] Test language switching (EN ↔ AR)
- [ ] Verify all links (WhatsApp, email, phone)
- [ ] Test responsive design (mobile, tablet, desktop)
- [ ] Check keyboard navigation (Tab through all elements)
- [ ] Validate RTL layout in Arabic mode
- [ ] Test in multiple browsers (Chrome, Firefox, Safari, Edge)
- [ ] Verify smooth scroll animations
- [ ] Check print layout (Ctrl+P)
- [ ] Test with screen readers (VoiceOver, NVDA)
- [ ] Validate HTML5 markup
- [ ] Check page load speed

## 📱 Browser Support

**Fully Supported**
- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

**Mobile**
- iOS Safari 14+
- Chrome Mobile 90+
- Samsung Internet 14+

**Graceful Degradation**
- Older browsers receive simpler layout
- Reduced motion for accessibility preferences
- Print-friendly fallback styles

## 🔒 Security Notes

- No external scripts (except Google Fonts)
- No data collection or cookies
- HTTPS recommended for production
- Regular dependency updates not needed (vanilla stack)

## 📈 Performance Metrics

**Target Scores**
- Lighthouse Performance: 95+
- Lighthouse Accessibility: 100
- Lighthouse Best Practices: 100
- Lighthouse SEO: 100

**File Size**
- HTML: ~46 KB (uncompressed)
- Total page weight: ~50 KB + fonts

## 🤝 Contributing

This is a client project. For internal team changes:

1. Create feature branch: `git checkout -b feature/your-change`
2. Make changes and test thoroughly
3. Commit: `git commit -m "Description of changes"`
4. Push: `git push origin feature/your-change`
5. Create pull request for review

## 📞 Contact & Support

**NordCloud Qatar**
- 📧 Email: info@nordcloud.qa
- 📱 WhatsApp: +974 XXXX XXXX
- 🌐 Website: https://nordcloud.qa
- 📍 Location: Ras Bufontas Free Zone, Doha, Qatar

**Technical Support**
For website issues or changes, contact the development team.

## 📄 License

Copyright © 2025 NordCloud Qatar. All rights reserved.

---

**Built with care for Qatar's digital transformation** 🇶🇦

*Last updated: November 2025*
