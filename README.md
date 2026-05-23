# Nexova - Premium Mobile Accessories Website

A modern, responsive website for Nexova mobile accessories featuring product showcases, company information, and contact forms.

## 📋 Project Structure

```
Nexova-tech-website/
├── index.html              # Main HTML file
├── styles.css              # Global styles and responsive design
├── script.js               # Interactive JavaScript
├── README.md               # This file
└── .github/
    └── workflows/
        └── deploy.yml      # Automated deployment workflow
```

## ✨ Features

- **Responsive Design**: Mobile-first approach that works on all devices
- **Modern UI**: Clean and professional interface using CSS Grid and Flexbox
- **Product Showcase**: Featured product cards with hover effects
- **Contact Form**: Interactive contact section for customer inquiries
- **Smooth Navigation**: Smooth scrolling and navigation experience
- **Performance**: Optimized assets and fast loading times

## 🚀 Getting Started

### Local Development

1. Clone the repository:
```bash
git clone https://github.com/nerazanadh/Nexova-tech-website.git
cd Nexova-tech-website
```

2. Open `index.html` in your browser or use a local server:
```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (with http-server)
npx http-server
```

3. Visit `http://localhost:8000` in your browser

## 📦 Deployment

This project uses GitHub Pages for automatic deployment. Every push to the `main` branch triggers the deployment workflow.

### Automatic Deployment

The `.github/workflows/deploy.yml` workflow automatically:
- Builds the website
- Runs quality checks
- Deploys to GitHub Pages

### Manual Deployment

1. Enable GitHub Pages:
   - Go to repository Settings → Pages
   - Select "Deploy from a branch"
   - Choose `main` branch and `/root` folder

2. Your site will be available at: `https://nerazanadh.github.io/Nexova-tech-website/`

## 🎨 Customization

### Colors
Edit the CSS variables in `styles.css`:
```css
:root {
    --primary-color: #2563eb;
    --secondary-color: #1e40af;
    --text-color: #1f2937;
    --light-bg: #f9fafb;
}
```

### Content
- Edit `index.html` to modify page content
- Update product information in the Products section
- Customize the About and Contact sections

### Styling
- All styles are in `styles.css`
- Mobile responsiveness is handled with media queries
- Font and spacing can be customized via CSS variables

## 🔄 GitHub Pages Configuration

This repository is configured to use GitHub Pages with:
- **Source**: main branch
- **Build**: Static site (no build process)
- **URL**: `https://nerazanadh.github.io/Nexova-tech-website/`

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📝 License

This project is open source and available under the MIT License.

## 👨‍💻 Author

- **nerazanadh** - Initial work

## 🤝 Contributing

Feel free to fork this repository and submit pull requests with improvements.

---

Made with ❤️ for Nexova Mobile Accessories
