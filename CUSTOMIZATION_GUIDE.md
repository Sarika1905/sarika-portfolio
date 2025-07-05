# Portfolio Customization Guide

This guide will help you customize your personal portfolio website easily.

## 1. Changing Colors

### Main Colors (in styles.css)
Open `styles.css` and look for the `:root` section at the top:

```css
:root {
    --primary-color: #20b2aa; /* Turquoise - Change this for main accent color */
    --secondary-color: #000000; /* Black - Change this for text/headers */
    --accent-color: #ffffff; /* White - Change this for backgrounds */
    --text-dark: #333333; /* Dark text color */
    --text-light: #666666; /* Light text color */
    --background-light: #f8f9fa; /* Light background sections */
}
```

### Popular Color Combinations:
- **Blue Theme**: Change `--primary-color` to `#007bff`
- **Purple Theme**: Change `--primary-color` to `#6f42c1`
- **Green Theme**: Change `--primary-color` to `#28a745`
- **Orange Theme**: Change `--primary-color` to `#fd7e14`

## 2. Updating Personal Information

### In index.html, find and change:

**Name and Title (Hero Section):**
```html
<h1>Sarika Kanetkar</h1>
<h2>UI/UX Designer</h2>
<p class="hero-tagline">Crafting intuitive and human-centered digital experiences</p>
```

**About Me Text:**
Look for the about section and update your background, certifications, and projects.

**Contact Information:**
Find the contact section and update email and social links.

## 3. Adding Your Own Projects

### Replace Project Cards:
In the projects section, each project has this structure:
```html
<div class="project-card">
    <div class="project-image">
        <img src="YOUR_IMAGE_URL" alt="Project Name">
    </div>
    <div class="project-content">
        <h3>Project Name</h3>
        <p class="project-role">Your Role</p>
        <p class="project-tools">Tools: List your tools</p>
        <p class="project-summary">Brief description of the project</p>
        <div class="project-tags">
            <span class="tag">Tag 1</span>
            <span class="tag">Tag 2</span>
        </div>
    </div>
</div>
```

## 4. Updating Your Resume

### Replace the Resume PDF:
1. Save your resume as a PDF file
2. Replace the file in `assets/resume.pdf`
3. The download button will automatically link to your new resume

### Update Timeline:
In the resume section, modify the timeline items:
```html
<div class="timeline-item">
    <div class="timeline-date">YEAR - YEAR</div>
    <div class="timeline-content">
        <h3>Job Title</h3>
        <p class="company">Company Name</p>
        <p>Description of your role and achievements</p>
    </div>
</div>
```

## 5. Customizing Skills

### In the Skills Section:
Add or remove skills from each category:
```html
<ul class="skill-list">
    <li><i class="fas fa-check"></i> Your Skill Name</li>
    <li><i class="fas fa-check"></i> Another Skill</li>
</ul>
```

## 6. Changing Images

### Hero Section Image:
Replace the profile image URL in the hero section:
```html
<img src="YOUR_PROFILE_IMAGE_URL" alt="Your Name" class="profile-image">
```

### Project Images:
Replace project image URLs in each project card.

### Hobby Gallery:
Update images in the "More About Me" section.

## 7. Adding New Sections

### To add a new section:
1. Add a navigation link in the navbar
2. Create the section in HTML
3. Add corresponding styles in CSS
4. Update the smooth scrolling in JavaScript

## 8. Fonts and Typography

### Change Font:
In `index.html`, replace the Google Fonts link:
```html
<link href="https://fonts.googleapis.com/css2?family=YOUR_FONT:wght@300;400;500;600;700&display=swap" rel="stylesheet">
```

Then update the CSS:
```css
body {
    font-family: 'YOUR_FONT', sans-serif;
}
```

## 9. Mobile Responsiveness

The site is already mobile-responsive, but you can adjust breakpoints in the CSS media queries:
```css
@media (max-width: 768px) {
    /* Tablet styles */
}

@media (max-width: 480px) {
    /* Mobile styles */
}
```

## 10. Quick Customization Tips

1. **Test Changes**: Save your files and refresh the browser to see changes
2. **Backup**: Keep a copy of the original files before making major changes
3. **Colors**: Use online color palette generators for professional color combinations
4. **Images**: Use high-quality images that are optimized for web (under 1MB each)
5. **Content**: Keep text concise and professional

## Need Help?

- Check the browser's developer tools (F12) for any errors
- Test on different devices to ensure responsiveness
- Use online validators to check your HTML and CSS

Remember: Small changes can make a big impact. Start with colors and content, then move to more advanced customizations!