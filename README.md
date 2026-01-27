# Personal Website

A modern, responsive personal website built with HTML, CSS, and JavaScript.

## Features

- ✨ Modern, clean design
- 📱 Fully responsive (mobile, tablet, desktop)
- 🎨 Smooth animations and transitions
- 🚀 Fast loading and optimized
- ♿ Accessible design
- 📧 Contact form
- 🎯 Smooth scrolling navigation

## Sections

1. **Hero Section** - Introduction and call-to-action
2. **About** - Personal background and statistics
3. **Projects** - Portfolio showcase
4. **Skills** - Technologies and tools
5. **Contact** - Contact information and form

## Getting Started

### Local Development

1. Clone or download this repository
2. Open `index.html` in your web browser
3. That's it! No build process required.

### Customization

1. **Personal Information**
   - Edit `index.html` and replace:
     - "Your Name" with your actual name
     - "your.email@example.com" with your email
     - Social media links with your profiles
     - Project descriptions and links

2. **Colors**
   - Edit CSS variables in `css/style.css`:
     ```css
     :root {
         --primary-color: #6366f1;
         --secondary-color: #8b5cf6;
         /* ... other colors */
     }
     ```

3. **Content**
   - Update project cards with your actual projects
   - Modify skills list to match your expertise
   - Add your own images to the `images/` folder

4. **Images**
   - Add project images to the `images/` folder
   - Update image paths in `index.html`
   - Recommended image size: 800x600px for project images

## Deployment

### Option 1: Netlify (Recommended - Easiest)

1. Go to [netlify.com](https://netlify.com)
2. Sign up for a free account
3. Drag and drop your project folder onto Netlify
4. Your site will be live at `your-site-name.netlify.app`
5. (Optional) Add a custom domain in Netlify settings

### Option 2: GitHub Pages

1. Create a GitHub repository
2. Push your code to GitHub:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git remote add origin https://github.com/yourusername/your-repo.git
   git push -u origin main
   ```
3. Go to repository Settings > Pages
4. Select branch: `main` and folder: `/ (root)`
5. Your site will be live at `username.github.io/repo-name`

### Option 3: Vercel

1. Go to [vercel.com](https://vercel.com)
2. Sign up with GitHub
3. Import your repository
4. Deploy automatically
5. Your site will be live at `your-site-name.vercel.app`

### Option 4: Cloudflare Pages

1. Go to [pages.cloudflare.com](https://pages.cloudflare.com)
2. Sign up for a free account
3. Connect your Git repository
4. Deploy automatically
5. Your site will be live at `your-site-name.pages.dev`

## Contact Form

The contact form currently shows an alert message. To make it functional, you have several options:

1. **Formspree** - Add their endpoint to the form action
2. **EmailJS** - Integrate their service
3. **Backend API** - Create your own backend endpoint
4. **Netlify Forms** - If hosting on Netlify, add `netlify` attribute to form

Example with Formspree:
```html
<form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

This project is open source and available under the MIT License.

## Credits

- Font: [Inter](https://fonts.google.com/specimen/Inter) by Google Fonts
- Icons: Emoji (can be replaced with icon libraries like Font Awesome)

---

**Made with ❤️ using HTML, CSS, and JavaScript**
