# Narrivex LLC - Company Website

A modern, responsive company website showcasing Narrivex LLC's AI-powered software solutions.

## About

Narrivex LLC is a software development company based in the Cincinnati, Ohio area, specializing in AI integration to create innovative tools for research and creative writing.

## Projects

- **SpecuLab**: AI-assisted research tool - [GitHub Repository](https://github.com/Narrivex/SpecuLab)
- **Author Beacon**: AI-assisted creative writing tool (In Development)

## Features

- ✨ Modern, clean design with smooth animations
- 📱 Fully responsive (mobile, tablet, desktop)
- 🎨 Professional color scheme optimized for tech companies
- ⚡ Fast loading static site
- 🔍 SEO optimized with meta tags and semantic HTML
- 🌐 Open Graph tags for social media sharing
- ♿ Accessible design with proper ARIA labels
- 🚀 Ready for deployment on GitHub Pages or custom domain

## Technology Stack

- **HTML5**: Semantic markup for better SEO
- **CSS3**: Modern styling with CSS variables, Grid, and Flexbox
- **JavaScript**: Vanilla JS for smooth interactions and animations
- **Google Fonts**: Inter and Space Grotesk for professional typography

## Deployment

### GitHub Pages

1. Go to your repository settings
2. Navigate to "Pages" in the left sidebar
3. Under "Source", select the branch you want to deploy (e.g., `main`)
4. Select the root folder (`/`)
5. Click "Save"
6. Your site will be available at `https://narrivex.github.io/website/`

### Custom Domain (narrivex.com)

#### Option 1: Using GitHub Pages with Custom Domain

1. Add a `CNAME` file to the repository root with your domain:
   ```
   narrivex.com
   ```

2. In your DNS provider (where you registered narrivex.com), add these records:
   ```
   Type    Name    Value
   A       @       185.199.108.153
   A       @       185.199.109.153
   A       @       185.199.110.153
   A       @       185.199.111.153
   CNAME   www     narrivex.github.io
   ```

3. In GitHub repository settings > Pages, enter your custom domain: `narrivex.com`

4. Enable "Enforce HTTPS" (may take a few minutes to be available)

#### Option 2: Traditional Web Hosting

1. Upload all files to your web hosting via FTP/SFTP:
   - `index.html`
   - `styles.css`
   - `script.js`
   - `assets/` folder

2. Ensure `index.html` is in the root directory of your domain

3. Test your site at `https://narrivex.com`

## Local Development

To view the site locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/Narrivex/website.git
   cd website
   ```

2. Open `index.html` in your browser, or use a local server:
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js (if you have http-server installed)
   npx http-server
   ```

3. Visit `http://localhost:8000` in your browser

## File Structure

```
website/
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js           # JavaScript functionality
├── assets/             # Images and other assets
│   └── favicon.svg     # Company favicon
├── .gitignore          # Git ignore file
├── README.md           # This file
└── LICENSE             # MIT License
```

## Customization

### Colors

Edit CSS variables in `styles.css`:
```css
:root {
    --primary-color: #3b82f6;    /* Blue */
    --secondary-color: #8b5cf6;   /* Purple */
    --accent-color: #06b6d4;      /* Cyan */
    /* ... */
}
```

### Content

- Company information: Edit text in `index.html`
- Projects: Update the Projects section in `index.html`
- Contact links: Modify the Contact section in `index.html`

### SEO

Update meta tags in the `<head>` section of `index.html`:
- `<title>`: Page title
- `<meta name="description">`: Site description
- `<meta name="keywords">`: Keywords for search engines
- Open Graph tags for social media

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## License

MIT License - see [LICENSE](LICENSE) file for details

## Contact

- **Company**: Narrivex LLC
- **Location**: Cincinnati, Ohio Area
- **GitHub**: [https://github.com/Narrivex](https://github.com/Narrivex)
- **Website**: [https://narrivex.com](https://narrivex.com)

---

Built with ❤️ by Narrivex LLC
