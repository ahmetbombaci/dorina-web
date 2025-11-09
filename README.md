# Dorina Strori, PhD - Personal Website

A modern, responsive personal website showcasing professional experience, expertise, and contact information.

## Features

- **Modern Design**: Clean, professional design with gradient accents
- **Fully Responsive**: Mobile-first approach, works on all devices (mobile, tablet, desktop)
- **Smooth Animations**: Engaging animations and transitions throughout
- **SEO-Friendly**: Semantic HTML structure optimized for search engines
- **Fast Loading**: No frameworks or heavy dependencies, pure HTML/CSS/JavaScript
- **Accessible**: Built with accessibility best practices in mind

## Structure

```
dorina-web/
├── index.html      # Main HTML file
├── styles.css      # Stylesheet with custom CSS variables
├── script.js       # Interactive features and animations
└── README.md       # This file
```

## Sections

1. **Hero Section**: Professional introduction with name, title, and current positions
2. **About**: Detailed professional background and expertise
3. **Expertise**: Key areas of specialization displayed in cards
4. **Experience**: Professional timeline with positions and responsibilities
5. **Contact**: Contact form and professional links

## Setup Instructions

### Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/ahmetbombaci/dorina-web.git
   cd dorina-web
   ```

2. Open `index.html` in your browser:
   - Double-click the file, or
   - Use a local server (recommended):
     ```bash
     python -m http.server 8000
     # or
     npx serve
     ```

3. Visit `http://localhost:8000` in your browser

### GitHub Pages Deployment

This website is configured to be hosted on GitHub Pages.

1. **Enable GitHub Pages**:
   - Go to your repository on GitHub
   - Navigate to Settings → Pages
   - Under "Source", select the branch: `claude/debug-incomplete-query-011CUwjhz3tLvT9jva1eSgXc` or `main`
   - Click "Save"

2. **Access your site**:
   - Your site will be available at: `https://ahmetbombaci.github.io/dorina-web/`
   - It may take a few minutes for the site to go live

### Custom Domain (Optional)

To use a custom domain:

1. Create a `CNAME` file in the root directory with your domain name:
   ```
   yourdomain.com
   ```

2. Configure DNS records with your domain provider:
   - Add a CNAME record pointing to `ahmetbombaci.github.io`

3. In GitHub Pages settings, enter your custom domain

## Customization

### Colors

Edit CSS variables in `styles.css`:

```css
:root {
    --primary-color: #2563eb;
    --secondary-color: #8b5cf6;
    --accent-color: #ec4899;
    /* ... other variables ... */
}
```

### Content

- **Personal Information**: Edit `index.html` sections directly
- **Experience**: Add/modify experience items in the Experience section
- **Expertise**: Update expertise cards to reflect your skills
- **Contact Form**: Currently shows success message locally

### Contact Form Integration

To enable actual email functionality, integrate with a form backend service:

#### Option 1: Formspree
```html
<form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
```

#### Option 2: EmailJS
1. Sign up at [EmailJS](https://www.emailjs.com/)
2. Add the EmailJS SDK to `index.html`
3. Update the form handler in `script.js`

#### Option 3: Netlify Forms
If hosting on Netlify, add `netlify` attribute to form:
```html
<form netlify>
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Performance

- **Load Time**: < 1 second
- **Page Size**: < 100KB (excluding images)
- **No Dependencies**: Pure vanilla JavaScript, no frameworks

## License

Copyright © 2025 Dorina Strori, PhD. All rights reserved.

## Contact

For questions or collaboration opportunities:
- LinkedIn: [linkedin.com/in/dorina-strori](https://www.linkedin.com/in/dorina-strori/)

---

Built with HTML, CSS, and JavaScript. Hosted on GitHub Pages.
