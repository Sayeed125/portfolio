## Md. Abu Sayeed - Personal Portfolio Website

A modern, responsive, and professional portfolio website showcasing academic qualifications, research, professional experience, projects, and skills.

### 🎯 Features

✅ **Responsive Design** - Works seamlessly on desktop, tablet, and mobile devices  
✅ **Dark/Light Mode** - Toggle between dark and light themes with preference saving  
✅ **Modern UI/UX** - Clean, professional design with smooth animations  
✅ **Fixed Navigation** - Easy navigation with active link highlighting  
✅ **Hero Section** - Eye-catching introduction with call-to-action buttons  
✅ **About Section** - Professional summary with key statistics  
✅ **Education Timeline** - Interactive timeline of academic achievements  
✅ **Professional Experience** - Career progression with detailed achievements  
✅ **Research & Publications** - Showcase of research work and academic contributions  
✅ **Featured Projects** - Display of completed projects with descriptions  
✅ **Skills & Expertise** - Organized skills by category  
✅ **Contact Section** - Contact information and functional contact form  
✅ **Social Links** - Integration with LinkedIn, GitHub, Twitter, Google Scholar  
✅ **Scroll Animations** - Elements animate as you scroll down  
✅ **Mobile Menu** - Hamburger navigation for smaller screens  
✅ **Scroll-to-Top Button** - Quick navigation back to top  

### 📁 File Structure

```
portfolio/
├── index.html              # Main HTML file
├── css/
│   └── styles.css          # Complete responsive styling (1200+ lines)
├── js/
│   └── script.js           # Interactive functionality
├── assets/                 # Images directory (to be created)
│   ├── profile.jpg         # Profile picture
│   ├── project1.jpg        # Project images
│   ├── project2.jpg
│   ├── project3.jpg
│   └── project4.jpg
└── README.md               # This file
```

### 🚀 Quick Start

#### 1. **Setup Your Profile Picture**
- Add your professional headshot as `assets/profile.jpg`
- Or update the image URL in `index.html` (currently using placeholder)

#### 2. **Customize Content**
Edit `index.html` and update:
- **Hero Section**: Your name, subtitle, and description
- **About Section**: Professional summary and statistics
- **Education**: Your degrees, universities, and dates
- **Experience**: Job titles, organizations, and achievements
- **Research**: Focus areas, publications, and presentations
- **Projects**: Project details, descriptions, and technologies
- **Skills**: Your technical and professional competencies
- **Contact**: Email, phone, location, and social links

#### 3. **Update Social Links**
Replace placeholder URLs with your actual profiles:
```html
<!-- LinkedIn -->
<a href="https://linkedin.com/in/YOUR-PROFILE" target="_blank">

<!-- GitHub -->
<a href="https://github.com/Sayeed125" target="_blank">

<!-- Twitter -->
<a href="https://twitter.com/YOUR-HANDLE" target="_blank">

<!-- Google Scholar -->
<a href="https://scholar.google.com/citations?user=YOUR-ID" target="_blank">
```

#### 4. **Deploy to GitHub Pages**
1. Ensure the repository is set to **Public**
2. Go to Settings → Pages
3. Select `main` as the source branch
4. Your site will be live at: `https://Sayeed125.github.io/portfolio`

### 🎨 Customization Guide

#### Change Color Scheme
Edit CSS variables in `css/styles.css`:

```css
:root {
    --primary-color: #2563eb;      /* Main blue color */
    --secondary-color: #f59e0b;    /* Amber accent color */
    --text-dark: #1f2937;          /* Dark text */
    --bg-light: #f9fafb;           /* Light background */
    /* ... more variables */
}
```

**Popular Color Combinations:**
- Professional: `#2563eb` (blue) + `#1e40af` (dark blue)
- Vibrant: `#7c3aed` (purple) + `#f59e0b` (amber)
- Minimal: `#1f2937` (dark) + `#6b7280` (gray)

#### Modify Typography
Update font sizes in `css/styles.css`:
```css
h1 { font-size: 3.5rem; }  /* Hero title */
h2 { font-size: 2.5rem; }  /* Section titles */
p { font-size: 1rem; }     /* Body text */
```

#### Add/Remove Sections
To add a new section:
1. Add HTML in `index.html`
2. Style with CSS in `css/styles.css`
3. Add navigation link in navbar
4. JavaScript animations will apply automatically

### 📱 Browser Compatibility

- ✅ Chrome/Edge (Latest)
- ✅ Firefox (Latest)
- ✅ Safari (Latest)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

### 🔧 Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Advanced styling with custom properties and flexbox/grid
- **JavaScript (ES6+)** - Interactivity and animations
- **Font Awesome 6.4.0** - Icon library
- **Google Fonts** - Poppins font family
- **Responsive Design** - Mobile-first approach

### 📋 Sections Detailed

#### Hero Section
- Your name as main title (with typing animation)
- Professional subtitle (Data Analytics Officer & PhD Candidate)
- Brief description highlighting your role and organization
- CTA buttons (View My Work, Get In Touch)
- Profile image with hover effects
- Social media links (LinkedIn, GitHub, Twitter, Google Scholar)

#### About
- Professional summary (2-3 paragraphs)
- Key statistics:
  - Years of Experience
  - Research Projects Completed
  - Publications
  - Technical Skills

#### Education
- Timeline of educational qualifications
- University names and dates
- Degrees and focus areas
- GPA/Honours (optional)

#### Professional Experience
- Timeline of career positions
- Organization names and dates
- Role descriptions
- Key achievements and responsibilities

#### Research & Publications
- Research focus areas (5-6 areas)
- Recent publications (with journal names)
- International presentations and conferences
- Research highlights and achievements

#### Projects
- 4 featured projects showcasing your work
- Project images, descriptions, and technologies
- Clickable links to project details/repositories
- Badge tags for project type and methodology

#### Skills
- 6 skill categories:
  - Data Analytics & Statistics
  - Programming Languages
  - Data Visualization & BI Tools
  - Research Methodologies
  - Domain Expertise
  - Soft Skills
- 8-10 skills per category as interactive tags

#### Contact
- Contact information (email, phone, location, organization)
- Functional contact form
- Social media links
- Easy-to-reach contact details

### ⚙️ JavaScript Features

1. **Theme Toggle** - Save dark/light mode preference to localStorage
2. **Mobile Menu** - Responsive hamburger menu for mobile devices
3. **Smooth Scrolling** - Enhanced navigation with smooth scroll to sections
4. **Scroll Animations** - Elements fade in and slide as you scroll
5. **Form Validation** - Basic validation for contact form
6. **Active Navigation** - Highlights current section in navbar
7. **Navbar Scroll Effect** - Shadow effect on scroll
8. **Scroll-to-Top Button** - Quick navigation to top
9. **Console Welcome** - Personalized message in developer console

### 📧 Enable Email Functionality

#### Option 1: FormSubmit.co (Recommended - Free & Easy)
1. Update form action in `index.html`:
```html
<form class="contact-form" id="contactForm" action="https://formsubmit.co/your-email@example.com" method="POST">
```
2. First submission requires email confirmation
3. Emails will be sent to your address

#### Option 2: EmailJS (JavaScript-based)
1. Sign up at [emailjs.com](https://emailjs.com)
2. Add script in `index.html`:
```html
<script type="text/javascript" src="https://cdn.jsdelivr.net/npm/@emailjs/browser@4/dist/index.min.js"></script>
```
3. Configure in `js/script.js`

#### Option 3: Backend API
Create your own backend endpoint and update form submission in `js/script.js`

### 🖼️ Recommended Image Dimensions

- **Profile Picture**: 300x300px (square)
- **Project Images**: 400x250px (landscape)
- **Thumbnails**: 100x100px (square)

**Formats**: JPG or PNG, compressed for web (< 200KB each)

### 🔒 Privacy & Security

- No personal data collection without explicit consent
- Contact form submission is client-side (use external service for actual email)
- Social media links open in new tabs
- Secure HTTPS recommended for deployment

### 📊 Performance Tips

1. **Optimize Images**
   - Compress using [TinyPNG](https://tinypng.com) or [ImageOptim](https://imageoptim.com)
   - Use WebP format for better compression
   - Lazy load images below the fold

2. **Minify Assets**
   - Minify CSS and JavaScript for production
   - Use tools like [minifier.org](https://minifier.org)

3. **Cache Strategy**
   - Enable browser caching
   - Use service workers for offline support

4. **SEO Optimization**
   - Update meta description
   - Add relevant keywords
   - Create sitemap.xml
   - Submit to Google Search Console

### 🎯 Best Practices

1. **Content**
   - Keep descriptions concise and impactful
   - Use action words in achievements
   - Update content regularly
   - Proofread for errors

2. **Design**
   - Maintain consistent spacing
   - Use professional images
   - Test on multiple devices
   - Ensure good color contrast

3. **Functionality**
   - Test all links
   - Verify form submission
   - Test theme toggle
   - Check mobile menu

4. **Performance**
   - Test page load speed
   - Optimize for Core Web Vitals
   - Use CDNs for assets
   - Monitor analytics

### 📈 Analytics

Add Google Analytics for tracking:

```html
<!-- In <head> section -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_ID');
</script>
```

### 🐛 Troubleshooting

| Issue | Solution |
|-------|----------|
| Images not showing | Check file paths, ensure assets folder exists |
| Dark mode not working | Clear localStorage, check CSS variables |
| Mobile menu not closing | Check JavaScript console for errors |
| Links not working | Verify href attributes match section IDs |
| Form not submitting | Configure email service, check console errors |
| Styling issues | Clear browser cache, check CSS file is linked |

### 📚 Resources

- [Font Awesome Icons](https://fontawesome.com/icons)
- [CSS Tricks](https://css-tricks.com)
- [MDN Web Docs](https://developer.mozilla.org)
- [GitHub Pages Documentation](https://pages.github.com)
- [Google Fonts](https://fonts.google.com)

### 🤝 Contributing

Feel free to customize and improve this portfolio template. Some ideas:
- Add more sections (certifications, awards, testimonials)
- Create project detail pages
- Add blog section
- Implement filtering for projects/skills
- Add animations library (AOS.js, Animate.css)

### 📝 License

This portfolio template is free to use and modify for personal use.

### 📞 Need Help?

For issues or questions:
1. Check the code comments
2. Review the CSS variables documentation
3. Test in browser console
4. Verify file structure
5. Check GitHub Pages settings

### ✨ Final Checklist

Before deployment:
- [ ] Update all personal information
- [ ] Add profile picture
- [ ] Add project images
- [ ] Update all social links
- [ ] Configure email service (optional)
- [ ] Test on mobile devices
- [ ] Test dark/light mode
- [ ] Test all navigation links
- [ ] Test contact form
- [ ] Check performance (Lighthouse)
- [ ] Set up GitHub Pages
- [ ] Verify custom domain (optional)

---

**Portfolio Created For**: Md. Abu Sayeed  
**Role**: Data Analytics Officer | PhD Candidate  
**Organization**: Development Research Initiative (dRi)  
**Created**: May 3, 2026

---

### 🎉 Your Portfolio is Ready!

Your professional portfolio website is now set up and ready to showcase your:
- ✨ Academic Qualifications
- 🔬 Research & Publications
- 💼 Professional Experience
- 🚀 Notable Projects
- 💪 Skills & Expertise
- 📍 Contact Information

**Good luck with your career and PhD journey!** 🎓
