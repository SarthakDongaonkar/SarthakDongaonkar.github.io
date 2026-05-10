## 🌟 My Professional Profile Website

This is a modern, fully responsive profile website built with pure HTML, CSS, and JavaScript. Perfect for showcasing your professional presence on Twitter, LinkedIn, Instagram, and more!

### ✨ Features

- **Hero Section**: Eye-catching introduction with profile avatar and social links
- **About Section**: Personal bio and statistics
- **Profiles & Roles**: Display your profiles across different platforms
- **Experience Timeline**: Showcase your work experience with companies and roles
- **Co-curricular Activities**: Highlight achievements, speaking engagements, and contributions
- **Featured Projects**: Display your best work with images, descriptions, and links
- **Skills Section**: Organized by categories (Frontend, Backend, Tools, Soft Skills)
- **Gallery**: Image gallery with lightbox effect for photos and event memories
- **Contact Section**: Multiple ways to get in touch with contact form
- **Responsive Design**: Works beautifully on all devices
- **Dark/Light Mode Support**: Automatically adapts to user preferences
- **Smooth Animations**: Professional transitions and interactive elements

### 📁 File Structure

```
├── index.html          # Main HTML file with all sections
├── styles.css          # Comprehensive styling with CSS Grid & Flexbox
├── script.js           # Interactive features and animations
└── README.md           # This file
```

### 🎨 Customization Guide

#### 1. Update Personal Information (index.html)

Find and replace these sections with your information:

**Hero Section:**
- Line 44: Replace "Sarthak Dongaonkar" with your name
- Line 45: Update the subtitle/title
- Line 46: Change the bio text
- Line 49-57: Update social media links with your URLs
- Line 40: Replace avatar image URL

**About Section:**
- Lines 81-82: Update your about text
- Lines 90-99: Modify the statistics

**Profiles Section (Lines 107-137):**
- Update profile names, usernames, and links
- Change icons using Font Awesome classes

**Experience Section (Lines 145-206):**
- Add your work experience with companies and dates
- Update roles and achievements
- Modify technologies/skills used

**Co-curricular Activities (Lines 214-272):**
- Replace with your achievements
- Update icons and descriptions
- Add your dates and accomplishments

**Projects Section (Lines 280-342):**
- Update project titles and descriptions
- Replace placeholder images with your project screenshots
- Update project links (GitHub, live demo)
- Add your technologies

**Skills Section (Lines 350-395):**
- Organize skills by categories
- Replace with your actual technologies

**Gallery Section (Lines 403-455):**
- Replace placeholder images with your photos
- Update captions for each gallery item

**Contact Section (Lines 463-505):**
- Update your email, phone, location, and website
- These appear in both contact info and form submission

#### 2. Update Images

Replace all placeholder images:

```
https://via.placeholder.com/150/6366f1/ffffff?text=SD
```

**Options:**
- Upload images to your repo and use relative paths: `./images/photo.jpg`
- Use your own image hosting service
- Use services like Imgur, Cloudinary, or similar

#### 3. Customize Colors

Edit the CSS variables in `styles.css` (Lines 9-19):

```css
:root {
    --primary: #6366f1;      /* Main color */
    --secondary: #8b5cf6;    /* Secondary color */
    --accent: #ec4899;       /* Accent color */
    --dark: #0f172a;         /* Dark text */
    --light: #f8fafc;        /* Light background */
    --gray: #64748b;         /* Gray text */
    --border: #e2e8f0;       /* Border color */
}
```

#### 4. Update Social Media Links

Replace these URLs with your actual profiles:
- `https://twitter.com/yourhandle`
- `https://linkedin.com/in/yourprofile`
- `https://instagram.com/yourhandle`
- `https://github.com/yourhandle`
- `mailto:your.email@example.com`

### 🚀 Deployment

Your site is hosted on GitHub Pages at:
```
https://SarthakDongaonkar.github.io
```

**To deploy:**
1. Make changes to the files
2. Commit and push to your repository
3. Visit your GitHub Pages URL (it updates automatically)

### 📱 Sharing on Social Media

**Perfect for:**
- Twitter Bio: Add link in bio with short description
- LinkedIn About Section: Link to your profile page
- Instagram Bio: Use link aggregator if needed
- GitHub: Link from your GitHub profile

### 🎯 Tips for Best Results

1. **High-Quality Images**: Use clear, professional photos
2. **Keep Content Updated**: Regularly update experience and projects
3. **Professional URLs**: Use custom domain if possible
4. **Mobile Testing**: Test on mobile devices regularly
5. **SEO**: Add meta tags and descriptions for better search visibility
6. **Analytics**: Consider adding Google Analytics to track visitors

### 🛠️ Customization Examples

**To add a new section:**

1. Add HTML in the appropriate location
2. Add CSS styling in `styles.css`
3. Add any JavaScript functionality in `script.js`
4. Update navigation links in the navbar

**To add a new social platform:**

```html
<a href="https://yourplatform.com/yourprofile" class="social-btn" target="_blank">
    <i class="fab fa-yourplatform"></i>
</a>
```

### 📚 Resources

- **Font Awesome Icons**: https://fontawesome.com
- **Google Fonts**: https://fonts.google.com
- **Color Palettes**: https://coolors.co
- **Image Hosting**: https://imgur.com, https://cloudinary.com

### 💡 Future Enhancements

Consider adding:
- Dark mode toggle button
- Blog section
- Resume/CV download
- Case studies
- Video testimonials
- Newsletter signup
- Live chat integration
- Search functionality

### 📄 License

This template is free to use and customize for personal use.

### 🤝 Support

For issues or customization help, refer to the HTML comments in each section or contact your developer.

---

**Happy sharing! 🚀**
