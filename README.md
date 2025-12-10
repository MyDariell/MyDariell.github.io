# Portfolio Website

A simple, clean, and responsive portfolio website template.

## Features

- Responsive design that works on all devices
- Modern gradient hero section
- Projects showcase grid
- Skills section
- Contact section with social links
- Smooth scrolling navigation
- Clean and professional styling

## Customization Guide

### 1. Update Your Information

Edit `index.html` and replace the following:

- **[Your Name]** - Replace with your actual name (appears in multiple places)
- **Job title/subtitle** - Change "Web Developer | Designer | Problem Solver"
- **About section** - Write your own bio
- **Projects** - Add your actual projects with descriptions and links
- **Skills** - Update with your specific skills and technologies
- **Contact links** - Update email, GitHub, LinkedIn, Twitter URLs

### 2. Customize Colors

Edit `style.css` and modify the CSS variables at the top:

```css
:root {
    --primary-color: #2563eb;      /* Main brand color */
    --secondary-color: #1e40af;    /* Darker shade */
    --text-color: #1f2937;         /* Main text color */
    --light-text: #6b7280;         /* Secondary text */
    --bg-color: #ffffff;           /* Background */
    --light-bg: #f9fafb;           /* Alternate background */
}
```

### 3. Update Hero Gradient

Find the `.hero` section in `style.css` and modify:

```css
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
```

## Deploy to GitHub Pages

### Option 1: User/Organization Site

1. Create a repository named `yourusername.github.io` (replace with your GitHub username)
2. Push these files to the repository
3. Your site will be live at `https://yourusername.github.io`

### Option 2: Project Site

1. Create a repository with any name
2. Push these files to the repository
3. Go to repository Settings → Pages
4. Under "Source", select the branch (usually `main`) and root folder
5. Click Save
6. Your site will be live at `https://yourusername.github.io/repository-name`

### Git Commands to Deploy

```bash
# Initialize git (if not already done)
git init

# Add all files
git add .

# Commit files
git commit -m "Initial portfolio commit"

# Add your GitHub repository as remote
git remote add origin https://github.com/yourusername/repository-name.git

# Push to GitHub
git push -u origin main
```

## Local Development

Simply open `index.html` in your web browser to view the site locally.

Or use a local server:

```bash
# Python
python -m http.server 8000

# Node.js (if you have http-server installed)
npx http-server
```

Then visit `http://localhost:8000` in your browser.

## Adding More Features

### Add Images

Create an `images` folder and add your photos, then update `index.html`:

```html
<img src="images/profile.jpg" alt="Your Name">
```

### Add JavaScript

Create a `script.js` file for interactive features:

```html
<script src="script.js"></script>
```

### Add More Sections

Copy any existing section in `index.html` and customize it:

```html
<section id="blog" class="blog">
    <div class="container">
        <h2 class="section-title">Blog</h2>
        <!-- Add content here -->
    </div>
</section>
```

## Browser Support

This template works on all modern browsers:
- Chrome
- Firefox
- Safari
- Edge

## License

Feel free to use this template for your own portfolio.
