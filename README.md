# Iqbal Rahmadhan - Data Analytics & AI Portfolio

GitHub Pages portfolio showcasing data analytics expertise, business intelligence experience, and agentic AI projects.

## 🌐 Live Site
**Visit**: [https://miqbalrp.github.io](https://miqbalrp.github.io)

## 🛠️ How to Update Content

### **Adding New Articles**

#### For Series Articles:
1. Open `index.html`
2. Find the appropriate series container
3. Add new `series-item` with proper badge numbering:
```html
<div class="series-item">
    <div class="series-badge">Part X</div>
    <h3><a href="YOUR_ARTICLE_URL" target="_blank">Article Title</a></h3>
    <p>Article description...</p>
    <div class="meta">Published on Platform • Date</div>
    <div class="tags">
        <span class="tag">Tag1</span>
        <span class="tag">Tag2</span>
    </div>
</div>
```

#### For Standalone Articles:
Add new `standalone-article` section:
```html
<div class="standalone-article">
    <h3><a href="YOUR_ARTICLE_URL" target="_blank">Article Title</a></h3>
    <p>Article description...</p>
    <div class="meta">Published on Platform • Date</div>
    <div class="tags">
        <span class="tag">Tag1</span>
        <span class="tag">Tag2</span>
    </div>
</div>
```

### **Adding New Repositories**
1. Find the GitHub repositories section
2. Add new repository item:
```html
<div class="item">
    <h3><a href="https://github.com/miqbalrp/repo-name" target="_blank">Repository Name</a></h3>
    <p>Repository description...</p>
    <div class="meta">Python</div>
    <div class="tags">
        <span class="tag">Tag1</span>
        <span class="tag">Tag2</span>
    </div>
    <a href="https://github.com/miqbalrp/repo-name" class="github-link" target="_blank">View Repository</a>
</div>
```

### **Updating About Section**
Modify the About Me section in `index.html`:
- Update years of experience
- Add new skills or technologies
- Update professional summary
- Modify skill tags as needed

### **Creating New Article Series**
1. Add new `series-container`:
```html
<div class="series-container">
    <button class="series-header" onclick="toggleSeries(this)">
        <span>📊 Series Name (X articles)</span>
        <span class="series-toggle">▼</span>
    </button>
    <div class="series-content">
        <!-- Add series-item elements here -->
    </div>
</div>
```

## 🚀 Deployment

### **Initial Setup**
1. Ensure repository name is `miqbalrp.github.io`
2. Go to repository Settings → Pages
3. Set source to "Deploy from a branch"
4. Select "main" branch and "/ (root)" folder
5. Save settings

### **Making Updates**
1. Edit `index.html` locally or on GitHub
2. Commit changes to main branch
3. GitHub Pages automatically rebuilds (2-5 minutes)
4. Check live site for updates

### **Custom Domain Setup (Optional)**
If you want to use a custom domain (e.g., `iqbalrahmadhan.com`):
1. **Purchase domain** from a domain registrar
2. **Update CNAME file**: Replace the commented line with your domain
3. **Configure DNS**: Point your domain to GitHub Pages
   - Add CNAME record: `www` → `miqbalrp.github.io`
   - Add A records for apex domain to GitHub's IPs
4. **Enable in GitHub**: Go to Settings → Pages → Custom domain
5. **Wait for verification** and SSL certificate setup

## 📁 Project Structure
```
miqbalrp.github.io/
├── index.html          # Main portfolio page (all content + SEO meta tags)
├── README.md           # This comprehensive documentation
├── LICENSE             # MIT License for open source compliance
├── favicon.ico         # Website icon for browser tabs/bookmarks
├── robots.txt          # SEO optimization for search engines
├── sitemap.xml         # Search engine indexing configuration
├── CNAME              # Custom domain support (ready for future use)
└── .gitignore         # Development files exclusion list
```

### **File Descriptions**
- **index.html**: Single-page portfolio with embedded CSS/JS, SEO optimized
- **README.md**: Complete documentation for maintenance and updates
- **LICENSE**: MIT License enabling others to learn from your code
- **favicon.ico**: Professional browser icon enhancing brand recognition
- **robots.txt**: Guides search engine crawlers for better SEO
- **sitemap.xml**: Helps search engines index your portfolio effectively
- **CNAME**: Prepared for custom domain (currently commented out)
- **.gitignore**: Keeps repository clean by excluding system files

## 🎨 Design System

### **Colors**
- **Primary Blue**: `#3498db` (links, buttons, accents)
- **Dark Blue**: `#2c3e50` (headings, main text)  
- **Light Blue**: `#e8f4fd` (tag backgrounds)
- **Gray**: `#bdc3c7` (borders, subtle elements)

### **Typography**
- **Font**: System fonts (-apple-system, BlinkMacSystemFont, Segoe UI)
- **Headings**: Bold, dark blue
- **Body**: Regular weight, readable spacing

## � Best Practices

### **Content Guidelines**
- **Keep descriptions concise** but informative
- **Use consistent date formats** (e.g., "Month DD, YYYY")
- **Tag articles appropriately** for discoverability
- **Order by recency** (newest first)

### **SEO Optimization**
- All content is visible by default (series expanded)
- Proper heading hierarchy (H1, H2, H3)
- Descriptive link text and meta information
- Clean, semantic HTML structure

### **Maintenance**
- **Regular updates**: Add new articles as published
- **Link validation**: Ensure all external links work
- **Content accuracy**: Keep descriptions current
- **Professional tone**: Maintain consistent voice

## 📊 Portfolio Highlights

**Platform Diversity**: Medium, Towards Data Science, Superteams.ai  
**Technical Range**: Traditional analytics → Modern AI systems  
**Publication Span**: 2023 - 2025 (consistent output)  
**Expertise Areas**: BI, Time Series, Statistics, Agentic AI  
**Code Examples**: 5 GitHub repositories with real implementations  
**Professional Setup**: Complete with SEO, licensing, and documentation  

## 🏆 Professional Standards

✅ **SEO Optimized**: Meta tags, sitemap, robots.txt  
✅ **Open Source**: MIT Licensed with comprehensive documentation  
✅ **Performance**: Single-page design with fast loading  
✅ **Accessibility**: Semantic HTML and responsive design  
✅ **Maintainable**: Clean code structure with detailed README  
✅ **Scalable**: Easy to add new articles and repositories  
✅ **Professional**: Favicon, proper file structure, and best practices  

---

**Built with**: HTML5, CSS3, JavaScript  
**SEO Ready**: Sitemap, robots.txt, meta tags  
**Licensed**: MIT License for open source compliance  
**Hosted on**: GitHub Pages with custom domain support  
**Last Updated**: September 2025  

🎉 **Production-ready portfolio showcasing data analytics and AI expertise!**
