# Professional Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript.

## Features

- **Responsive Design**: Works on all devices (desktop, tablet, mobile)
- **Modern UI/UX**: Clean and professional design with smooth animations
- **Interactive Elements**: Hover effects, scroll animations, and form validation
- **Sections Include**:
  - Hero section with profile image
  - About section with stats
  - Skills showcase
  - Work experience timeline
  - Project portfolio
  - Contact form

## Files Structure

```
Portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styling
├── script.js           # JavaScript functionality
├── Resume.pdf          # Your resume (already present)
├── img4.jpg           # Profile image 1 (already present)
├── IMG_20241008_121805.jpg # Profile image 2 (already present)
└── README.md          # This file
```

## Customization Guide

### 1. Personal Information
Edit `index.html` to update:
- **Line 35**: Change "Your Name" to your actual name
- **Line 36**: Update your title/profession
- **Line 38-41**: Update your description
- **Line 138-140**: Update statistics (years experience, projects, clients)

### 2. Contact Information
Update the contact section in `index.html`:
- **Line 369**: Your email address
- **Line 377**: Your phone number
- **Line 385**: Your location
- **Line 393**: Your LinkedIn profile

### 3. Social Media Links
Update social media links in `index.html`:
- **Lines 47-50**: Hero section social links
- **Lines 412-415**: Footer social links

### 4. Skills Section
Update your technical skills in `index.html` (Lines 156-223):
- Frontend Development skills
- Backend Development skills
- Database & Cloud technologies
- Tools & Other skills

### 5. Work Experience
Update your work experience in `index.html` (Lines 234-310):
- Job titles and companies
- Employment dates
- Responsibilities and achievements
- Technologies used

### 6. Projects Section
Update your projects in `index.html` (Lines 327-395):
- Project names and descriptions
- Technologies used
- Live demo and source code links

### 7. Images
- Replace `img4.jpg` with your professional headshot
- Replace `IMG_20241008_121805.jpg` with another professional photo
- Ensure images are properly sized (400x400px recommended for profile images)

### 8. Colors and Styling
To change the color scheme, edit `styles.css`:
- **Primary Color**: Search for `#667eea` and replace with your preferred color
- **Secondary Color**: Search for `#764ba2` and replace
- **Text Colors**: Update `#2c3e50` (headings) and `#666` (body text)

### 9. Resume
- Replace `Resume.pdf` with your updated resume
- Ensure the filename matches the link in the download button

## Usage Instructions

### Running the Portfolio

1. **Open with VS Code**:
   - Right-click on the Portfolio folder
   - Select "Open with Code"

2. **View in Browser**:
   - Open `index.html` in any modern web browser
   - Or use VS Code Live Server extension for live preview

3. **Live Server Setup** (Recommended):
   - Install "Live Server" extension in VS Code
   - Right-click on `index.html`
   - Select "Open with Live Server"
   - This provides live reload when you make changes

### Deployment Options

1. **GitHub Pages**:
   - Create a GitHub repository
   - Upload your files
   - Enable GitHub Pages in repository settings

2. **Netlify**:
   - Drag and drop your Portfolio folder to Netlify
   - Get instant live URL

3. **Vercel**:
   - Connect your GitHub repository
   - Auto-deploy on every commit

## Browser Compatibility

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers

## Responsive Breakpoints

- Desktop: 1200px and up
- Tablet: 768px to 1199px
- Mobile: 767px and below

## Performance Features

- Optimized CSS and JavaScript
- Lazy loading animations
- Smooth scrolling
- Efficient image handling

## Customization Tips

1. **Typography**: Uses Google Fonts (Inter) - change in `index.html` line 9
2. **Icons**: Uses Font Awesome - add more icons by including their classes
3. **Animations**: Modify animation durations in `script.js`
4. **Layout**: Grid and flexbox layouts are easily customizable in `styles.css`

## Testing Checklist

Before deploying:
- [ ] Test all navigation links
- [ ] Verify contact form works
- [ ] Check mobile responsiveness
- [ ] Test all external links
- [ ] Validate HTML and CSS
- [ ] Optimize images for web

## Support

For customization help:
1. Check browser developer tools for errors
2. Validate HTML/CSS syntax
3. Test JavaScript functionality
4. Ensure all file paths are correct

---

**Note**: Remember to update all placeholder content with your actual information before deploying!
