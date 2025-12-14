# Portfolio Website

A modern, responsive portfolio website showcasing AI Engineering and Full Stack Engineering skills. Built with vanilla HTML, CSS, and JavaScript for easy deployment on GitHub Pages.

## Features

- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Modern UI**: Clean, professional design with smooth animations
- **Smooth Navigation**: Fixed navbar with smooth scrolling
- **Project Filtering**: Filter projects by category (AI/ML or Full Stack)
- **Interactive Elements**: Hover effects, transitions, and scroll animations
- **Mobile-Friendly**: Hamburger menu for mobile navigation

## File Structure

```
Portfolio/
├── index.html          # Main portfolio page
├── styles.css          # All styling and responsive design
├── script.js           # Interactive functionality
├── README.md           # This file
└── .gitignore          # Git ignore file
```

## Customization Guide

### 1. Personal Information

#### Update Contact Information
Edit `index.html` and find the contact section:
- Replace `your.email@example.com` with your actual email
- Replace `yourusername` in GitHub and LinkedIn URLs with your actual usernames

#### Update Name and Title
In the hero section, the name "Muskan" is already set. Update the subtitle if needed.

### 2. About Section

Replace the placeholder text in the About section with your professional summary:
- Key achievements
- Career highlights
- What makes you unique
- Your professional journey

### 3. Skills Section

Update the skills to match your actual expertise:

**AI/ML Skills** - Replace placeholder skills with your actual skills:
- Python, TensorFlow, PyTorch, etc.
- Add or remove skill tags as needed

**Full Stack Skills** - Replace placeholder skills with your actual skills:
- JavaScript, React, Node.js, etc.
- Add or remove skill tags as needed

### 4. Experience Section

Add your work experience by duplicating the timeline item structure:

```html
<div class="timeline-item">
    <div class="timeline-marker"></div>
    <div class="timeline-content">
        <h3 class="timeline-title">Your Job Title</h3>
        <h4 class="timeline-company">Company Name</h4>
        <span class="timeline-date">Month Year - Month Year</span>
        <ul class="timeline-description">
            <li>Key achievement or responsibility</li>
            <li>Another key achievement</li>
            <li>Additional contribution</li>
        </ul>
    </div>
</div>
```

### 5. Projects Section

Add your projects by duplicating the project card structure:

**For AI/ML Projects:**
```html
<div class="project-card" data-category="ai">
    <div class="project-image">
        <div class="project-placeholder">AI Project</div>
    </div>
    <div class="project-content">
        <h3 class="project-title">Project Name</h3>
        <p class="project-description">Project description...</p>
        <div class="project-tech">
            <span class="tech-tag">Python</span>
            <span class="tech-tag">TensorFlow</span>
        </div>
        <div class="project-links">
            <a href="github-url" class="project-link" target="_blank">GitHub</a>
            <a href="demo-url" class="project-link" target="_blank">Demo</a>
        </div>
    </div>
</div>
```

**For Full Stack Projects:**
```html
<div class="project-card" data-category="fullstack">
    <!-- Same structure, change data-category to "fullstack" -->
</div>
```

### 6. Education Section

Add your education by duplicating the education card:

```html
<div class="education-card">
    <h3 class="education-degree">Degree Name</h3>
    <h4 class="education-school">University Name</h4>
    <span class="education-date">Year - Year</span>
    <p class="education-details">
        Relevant coursework, GPA, honors, etc.
    </p>
</div>
```

## Deployment to GitHub Pages

### Method 1: Using GitHub Web Interface

1. **Create a new repository** on GitHub
   - Repository name: `your-username.github.io` (replace with your GitHub username)
   - Make it public
   - Don't initialize with README (you already have one)

2. **Upload your files**
   - Click "uploading an existing file"
   - Drag and drop all your portfolio files
   - Commit the changes

3. **Enable GitHub Pages**
   - Go to Settings → Pages
   - Under "Source", select "Deploy from a branch"
   - Choose "main" branch and "/ (root)" folder
   - Click Save

4. **Access your site**
   - Your portfolio will be live at `https://your-username.github.io`
   - It may take a few minutes to deploy

### Method 2: Using Git Command Line

1. **Initialize Git repository**
   ```bash
   git init
   git add .
   git commit -m "Initial portfolio commit"
   ```

2. **Create GitHub repository**
   - Go to GitHub and create a new repository named `your-username.github.io`

3. **Connect and push**
   ```bash
   git remote add origin https://github.com/your-username/your-username.github.io.git
   git branch -M main
   git push -u origin main
   ```

4. **Enable GitHub Pages**
   - Go to repository Settings → Pages
   - Select "Deploy from a branch"
   - Choose "main" branch and "/ (root)" folder
   - Save

## Custom Domain (Optional)

If you want to use a custom domain:

1. Add a `CNAME` file in your repository root with your domain name
2. Configure DNS settings with your domain provider
3. Update GitHub Pages settings with your custom domain

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance Tips

- Optimize images before adding them (use WebP format when possible)
- Minimize custom fonts if loading time is a concern
- Consider lazy loading for images if you add many

## Troubleshooting

### GitHub Pages not updating?
- Clear your browser cache
- Wait 5-10 minutes for changes to propagate
- Check repository Settings → Pages for deployment status

### Styles not loading?
- Ensure `styles.css` is in the same directory as `index.html`
- Check file paths are correct (case-sensitive on some systems)

### Navigation not working?
- Ensure `script.js` is properly linked in `index.html`
- Check browser console for JavaScript errors

## License

This portfolio template is free to use and modify for personal and commercial projects.

## Credits

- Font: [Inter](https://fonts.google.com/specimen/Inter) by Google Fonts
- Built with vanilla HTML, CSS, and JavaScript
- No frameworks or dependencies required

---

**Need help?** Feel free to open an issue or reach out!

