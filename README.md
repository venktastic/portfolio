# Professional Product Manager Portfolio

A complete static website for GitHub Pages showcasing a product manager's professional profile with 8+ years of experience across AI Safety Tech, Healthcare, Sports Technology, and IoT Telematics.

## 🚀 Quick Start

1. **Fork this repository** to your GitHub account
2. **Enable GitHub Pages** in your repository settings
3. **Customize the content** by replacing placeholder text and images
4. **Deploy** - Your site will be live at `https://venktastic.github.io/MyPortfolio`

## 📁 Project Structure

```
MyPortfolio/
├── index.html                 # Main portfolio page
├── blog.html                  # Blog listing page
├── styles.css                 # Main stylesheet
├── script.js                  # JavaScript functionality
├── assets/                    # Images and media files
│   ├── favicon.ico           # Website favicon
│   ├── profile-photo-placeholder.jpg
│   ├── hero-photo-placeholder.jpg
│   ├── project-*-placeholder.jpg
│   └── blog-*-placeholder.jpg
├── projects/                  # Individual project case studies
│   ├── ai-safety-platform.html
│   ├── healthcare-workflow.html
│   ├── sports-analytics.html
│   ├── iot-fleet-management.html
│   └── ai-content-platform.html
└── blog/                     # Individual blog posts
    ├── product-storytelling.html
    └── [additional blog posts]
```

## 🎨 Design Features

- **Modern, Clean Aesthetic** with AI-themed accents
- **Fully Responsive** design (mobile-first approach)
- **Professional Typography** using Inter font family
- **Smooth Animations** and hover effects
- **Accessibility Focused** with proper semantic HTML
- **SEO Optimized** with comprehensive meta tags

## 🛠️ Customization Guide

### 1. Personal Information

Replace the following placeholders throughout the files:

- `Venkatesh Murthy N S` → Your actual name
- `venky890@gmail.com` → Your email address
- `https://www.linkedin.com/in/iamvenky/` → Your LinkedIn profile
- `https://github.com/venktastic` → Your GitHub username
- `https://yourusername.github.io/MyPortfolio` → Your actual GitHub Pages URL

### 2. Images

Replace placeholder images in the `assets/` directory:

#### Required Images:
- **Profile Photos**: `profile-photo-placeholder.jpg` (40x40px for nav, 300x300px for hero)
- **Hero Image**: `hero-photo-placeholder.jpg` (300x300px, circular crop)
- **Project Images**: `project-1-placeholder.jpg` through `project-5-placeholder.jpg` (400x200px)
- **Blog Images**: `blog-1-placeholder.jpg` through `blog-6-placeholder.jpg` (400x200px)
- **Favicon**: `favicon.ico` (16x16px or 32x32px)

#### Image Specifications:
- **Format**: JPG or PNG
- **Optimization**: Compress images for web (use tools like TinyPNG)
- **Alt Text**: Update alt attributes for accessibility

### 3. Project Case Studies

Update the project case studies in the `projects/` directory:

1. **Replace placeholder content** with your actual project details
2. **Update project metrics** and results
3. **Modify technical stacks** to reflect your technologies
4. **Add real project images** and screenshots
5. **Update project timelines** and roles

### 4. Blog Content

Customize the blog section:

1. **Update blog post titles** and descriptions
2. **Replace placeholder content** with your actual insights
3. **Add your own blog posts** following the existing structure
4. **Update publication dates** and reading times
5. **Modify categories** to match your expertise areas

### 5. Contact Form Integration

To integrate Google Forms:

1. **Create a Google Form** with the following fields:
   - Name (required)
   - Email (required)
   - WhatsApp Number
   - Reason for Contacting (dropdown: General Inquiry, Job Opportunity, Collaboration, Networking)

2. **Get the embed code** from Google Forms
3. **Replace the iframe src** in `index.html` with your form's embed URL
4. **Update the form ID** in the placeholder: `https://forms.gle/mho6aE3Wn5STteSB8`

### 6. Color Scheme

The website uses CSS custom properties for easy color customization:

```css
:root {
    --primary-color: #2563eb;      /* Main brand color */
    --accent-color: #06b6d4;       /* Accent color */
    --text-primary: #1e293b;       /* Main text color */
    --text-secondary: #64748b;     /* Secondary text color */
    /* ... other colors */
}
```

## 📱 Responsive Design

The website is fully responsive with breakpoints at:
- **Mobile**: < 768px
- **Tablet**: 768px - 1024px
- **Desktop**: > 1024px

## 🔧 Technical Features

### Built With:
- **HTML5** with semantic markup
- **CSS3** with custom properties and Grid/Flexbox
- **Vanilla JavaScript** for interactions
- **Font Awesome** for icons
- **Google Fonts** (Inter) for typography

### Performance Optimizations:
- **Optimized images** with proper sizing
- **Minified CSS** and JavaScript
- **Efficient animations** using CSS transforms
- **Lazy loading** for better performance
- **Debounced scroll events** for smooth interactions

### SEO Features:
- **Comprehensive meta tags** for all pages
- **Open Graph** tags for social sharing
- **Structured data** markup
- **Semantic HTML** structure
- **Optimized page titles** and descriptions

## 🚀 Deployment

### GitHub Pages Deployment:

1. **Fork the repository** to your GitHub account
2. **Go to repository Settings** → Pages
3. **Select source**: Deploy from a branch
4. **Choose branch**: main
5. **Save** - Your site will be available at `https://yourusername.github.io/MyPortfolio`

### Custom Domain (Optional):

1. **Add a CNAME file** to the root directory with your domain
2. **Configure DNS** to point to GitHub Pages
3. **Update all URLs** in the code to use your custom domain

## 📊 Analytics Integration

To add Google Analytics:

1. **Get your Google Analytics tracking ID**
2. **Add the tracking code** to the `<head>` section of all HTML files:

```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_TRACKING_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_TRACKING_ID');
</script>
```

## 🔍 SEO Optimization

The website includes comprehensive SEO features:

- **Meta descriptions** for all pages
- **Open Graph tags** for social sharing
- **Twitter Card** support
- **Structured data** markup
- **Optimized images** with alt text
- **Clean URL structure**
- **Fast loading times**

## 🎯 Content Guidelines

### Writing Style:
- **Professional yet approachable** tone
- **Data-driven insights** with human context
- **Clear, concise** communication
- **Storytelling approach** to case studies

### Key Themes:
- **Empathy-driven** product development
- **Data-informed** decision making
- **Human-centered** technology
- **Cross-industry** expertise
- **Innovation** through collaboration

## 🛡️ Security & Privacy

- **No tracking** by default (add analytics if needed)
- **HTTPS** enforced on GitHub Pages
- **No external dependencies** except fonts and icons
- **Privacy-focused** contact form integration

## 📈 Performance Metrics

Target performance goals:
- **Lighthouse Score**: 90+ across all categories
- **First Contentful Paint**: < 1.5s
- **Largest Contentful Paint**: < 2.5s
- **Cumulative Layout Shift**: < 0.1

## 🤝 Contributing

This is a personal portfolio template. If you find bugs or have suggestions:

1. **Fork the repository**
2. **Create a feature branch**
3. **Make your changes**
4. **Submit a pull request**

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🆘 Support

If you need help customizing this portfolio:

1. **Check the documentation** above
2. **Review the code comments** for guidance
3. **Open an issue** for specific problems
4. **Contact the maintainer** for complex customizations

## 🎉 Acknowledgments

- **Design inspiration** from modern portfolio trends
- **Typography** by Inter font family
- **Icons** by Font Awesome
- **Color palette** inspired by professional design systems

---

**Ready to showcase your product management expertise?** Start customizing this portfolio and launch your professional presence today!

For questions or support, please open an issue in the repository.
