# ILBBI Website

Official website for **Ilocandia Liberty Bible Baptist Institute** (ILBBI), a Christian ministry training institute located in Batac City, Ilocos Norte, Philippines.

## About ILBBI

ILBBI was founded in 2002 as a venture of faith to train Christians for effective ministry. The institute offers theological education with practical ministry experience, emphasizing soul winning, church planting, and missions work.

## Website Features

- **Responsive Design**: Mobile-friendly layout that works on all devices
- **Accessibility**: WCAG AA compliance with semantic HTML and keyboard navigation
- **SEO Optimized**: Structured data, meta tags, and search engine friendly URLs
- **GitHub Pages Ready**: Optimized for deployment on GitHub Pages hosting

## Project Structure

```
ilbbi-website/
├── index.html              # Homepage
├── about/                  # About ILBBI (history, mission)
├── academics/              # Academic programs
├── admissions/             # Admission requirements
├── faculty/                # Faculty and staff profiles
├── students/               # Current students and graduates
├── events/                 # Events and commencement
├── pledge/                 # ILBBI Pledge of Loyalty
├── contact/                # Contact information
├── assets/
│   ├── css/styles.css      # Main stylesheet
│   ├── js/main.js          # JavaScript functionality
│   ├── img/                # Images (placeholders)
│   └── docs/               # Documents (PDFs)
├── 404.html                # Custom 404 error page
├── .nojekyll               # Bypass Jekyll on GitHub Pages
├── sitemap.xml             # Search engine sitemap
├── robots.txt              # Search engine directives
└── README.md               # This file
```

## Deployment Instructions

### GitHub Pages Setup

1. **Upload Files**: Upload all website files to your GitHub repository
2. **Enable Pages**: Go to repository Settings → Pages
3. **Configure Source**: 
   - Source: "Deploy from a branch"
   - Branch: "main" 
   - Folder: "/ (root)" or "/docs" if you place files in a docs folder
4. **Wait for Build**: GitHub will automatically build and deploy your site
5. **Access Site**: Your site will be available at `https://username.github.io/repository-name/`

### Custom Domain (Optional)

To use a custom domain:
1. Add a `CNAME` file to the root directory with your domain name
2. Configure DNS settings with your domain provider
3. Enable "Enforce HTTPS" in GitHub Pages settings

### Local Development

To test locally:
1. Open `index.html` in a web browser, or
2. Use a local server: `python -m http.server 8000`
3. Visit `http://localhost:8000` in your browser

## Technical Details

### Technologies Used

- **HTML5**: Semantic markup with proper accessibility features
- **CSS3**: Modern responsive design with CSS Grid and Flexbox
- **Vanilla JavaScript**: Minimal JS for mobile navigation and interactions
- **SVG**: Scalable placeholder graphics
- **Font Loading**: Google Fonts with system fallbacks

### Browser Support

- Modern browsers (Chrome, Firefox, Safari, Edge)
- Internet Explorer 11+ (with graceful degradation)
- Mobile browsers (iOS Safari, Chrome Mobile)

### Performance Optimizations

- Lightweight CSS (under 12KB)
- Minimal JavaScript (under 4KB)
- Optimized images (SVG placeholders)
- Efficient font loading strategy
- No external dependencies except Google Fonts

## Content Management

### Updating Images

Replace placeholder images in `assets/img/` with actual photos:
- `logo-placeholder.svg` → Official ILBBI logo
- `faculty/faculty-placeholder.svg` → Faculty/staff portraits
- `students/student-placeholder.svg` → Student photos
- `event/event-placeholder.svg` → Event banners

### Updating Content

Content is stored directly in HTML files. Major content areas:
- **Mission/History**: `index.html` and `about/index.html`
- **Programs**: `academics/index.html`
- **Faculty**: `faculty/index.html`
- **Students**: `students/index.html`
- **Events**: `events/index.html`

### Adding New Content

1. **New Pages**: Create new folders with `index.html`
2. **Navigation**: Update navigation in all HTML files
3. **Sitemap**: Add new URLs to `sitemap.xml`
4. **Styles**: Add page-specific styles to `assets/css/styles.css`

## Accessibility Features

- Semantic HTML5 landmarks and structure
- ARIA labels and roles where appropriate
- Keyboard navigation support
- Skip-to-content links
- High contrast color scheme
- Screen reader compatible
- Proper heading hierarchy

## SEO Features

- Unique title and meta description for each page
- Open Graph tags for social media sharing
- Structured data (Organization and Event schema)
- XML sitemap for search engines
- Robots.txt for crawler directives
- Semantic URLs and proper heading structure

## Maintenance

### Regular Updates

- Update student/graduate lists annually
- Update faculty information as changes occur
- Add new events and remove outdated ones
- Review and update contact information
- Update copyright year in footer

### Technical Maintenance

- Test website functionality quarterly
- Check for broken links
- Update dependencies if any are added
- Monitor site performance and loading speeds
- Backup website files regularly

## License

This website was created for Ilocandia Liberty Bible Baptist Institute. All content is property of ILBBI unless otherwise noted.

## Support

For technical issues with the website, please contact the web administrator.
For ILBBI-related inquiries, please use the contact information provided on the website.

---

**Ilocandia Liberty Bible Baptist Institute**  
10-S Barani, City of Batac, Ilocos Norte 2906, Philippines  
*"To God be the Glory!"*
